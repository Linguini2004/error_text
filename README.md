# error_text
   Running setup.py install for Twisted ... error
    ERROR: Command errored out with exit status 1:
     command: 'c:\users\david\appdata\local\programs\python\python38-32\python.exe' -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\David\\AppData\\Local\\Temp\\pip-install-dcegoj9r\\Twisted\\setup.py'"'"'; __file__='"'"'C:\\Users\\David\\AppData\\Local\\Temp\\pip-install-dcegoj9r\\Twisted\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\David\AppData\Local\Temp\pip-record-8yygxett\install-record.txt' --single-version-externally-managed --compile --install-headers 'c:\users\david\appdata\local\programs\python\python38-32\Include\Twisted'
         cwd: C:\Users\David\AppData\Local\Temp\pip-install-dcegoj9r\Twisted\
    Complete output (946 lines):
    running install
    running build
    running build_py
    creating build
    creating build\lib.win32-3.8
    creating build\lib.win32-3.8\twisted
    copying src\twisted\copyright.py -> build\lib.win32-3.8\twisted
    copying src\twisted\plugin.py -> build\lib.win32-3.8\twisted
    copying src\twisted\_version.py -> build\lib.win32-3.8\twisted
    copying src\twisted\__init__.py -> build\lib.win32-3.8\twisted
    copying src\twisted\__main__.py -> build\lib.win32-3.8\twisted
    creating build\lib.win32-3.8\twisted\application
    copying src\twisted\application\app.py -> build\lib.win32-3.8\twisted\application
    copying src\twisted\application\internet.py -> build\lib.win32-3.8\twisted\application
    copying src\twisted\application\reactors.py -> build\lib.win32-3.8\twisted\application
    copying src\twisted\application\service.py -> build\lib.win32-3.8\twisted\application
    copying src\twisted\application\strports.py -> build\lib.win32-3.8\twisted\application
    copying src\twisted\application\__init__.py -> build\lib.win32-3.8\twisted\application
    creating build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\avatar.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\checkers.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\endpoints.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\error.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\interfaces.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\ls.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\manhole.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\manhole_ssh.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\manhole_tap.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\mixin.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\recvline.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\stdio.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\tap.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\telnet.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\ttymodes.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\unix.py -> build\lib.win32-3.8\twisted\conch
    copying src\twisted\conch\__init__.py -> build\lib.win32-3.8\twisted\conch
    creating build\lib.win32-3.8\twisted\cred
    copying src\twisted\cred\checkers.py -> build\lib.win32-3.8\twisted\cred
    copying src\twisted\cred\credentials.py -> build\lib.win32-3.8\twisted\cred
    copying src\twisted\cred\error.py -> build\lib.win32-3.8\twisted\cred
    copying src\twisted\cred\portal.py -> build\lib.win32-3.8\twisted\cred
    copying src\twisted\cred\strcred.py -> build\lib.win32-3.8\twisted\cred
    copying src\twisted\cred\_digest.py -> build\lib.win32-3.8\twisted\cred
    copying src\twisted\cred\__init__.py -> build\lib.win32-3.8\twisted\cred
    creating build\lib.win32-3.8\twisted\enterprise
    copying src\twisted\enterprise\adbapi.py -> build\lib.win32-3.8\twisted\enterprise
    copying src\twisted\enterprise\__init__.py -> build\lib.win32-3.8\twisted\enterprise
    creating build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\abstract.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\address.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\asyncioreactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\base.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\cfreactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\default.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\defer.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\endpoints.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\epollreactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\error.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\fdesc.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\gireactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\glib2reactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\gtk2reactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\gtk3reactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\inotify.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\interfaces.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\kqreactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\main.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\pollreactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\posixbase.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\process.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\protocol.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\pyuisupport.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\reactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\selectreactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\serialport.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\ssl.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\stdio.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\task.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\tcp.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\testing.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\threads.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\tksupport.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\udp.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\unix.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\utils.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\win32eventreactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\wxreactor.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\wxsupport.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_baseprocess.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_dumbwin32proc.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_glibbase.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_idna.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_newtls.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_pollingfile.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_posixserialport.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_posixstdio.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_producer_helpers.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_resolver.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_signals.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_sslverify.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_threadedselect.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_win32serialport.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\_win32stdio.py -> build\lib.win32-3.8\twisted\internet
    copying src\twisted\internet\__init__.py -> build\lib.win32-3.8\twisted\internet
    creating build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_buffer.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_capture.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_file.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_filter.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_flatten.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_format.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_global.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_io.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_json.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_legacy.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_levels.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_logger.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_observer.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_stdlib.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\_util.py -> build\lib.win32-3.8\twisted\logger
    copying src\twisted\logger\__init__.py -> build\lib.win32-3.8\twisted\logger
    creating build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\imap4.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\interfaces.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\pop3.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\pop3client.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\protocols.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\relay.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\smtp.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\_cred.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\_except.py -> build\lib.win32-3.8\twisted\mail
    copying src\twisted\mail\__init__.py -> build\lib.win32-3.8\twisted\mail
    creating build\lib.win32-3.8\twisted\names
    copying src\twisted\names\authority.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\cache.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\client.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\common.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\dns.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\error.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\hosts.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\resolve.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\root.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\secondary.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\server.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\srvconnect.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\tap.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\_rfc1982.py -> build\lib.win32-3.8\twisted\names
    copying src\twisted\names\__init__.py -> build\lib.win32-3.8\twisted\names
    creating build\lib.win32-3.8\twisted\pair
    copying src\twisted\pair\ethernet.py -> build\lib.win32-3.8\twisted\pair
    copying src\twisted\pair\ip.py -> build\lib.win32-3.8\twisted\pair
    copying src\twisted\pair\raw.py -> build\lib.win32-3.8\twisted\pair
    copying src\twisted\pair\rawudp.py -> build\lib.win32-3.8\twisted\pair
    copying src\twisted\pair\testing.py -> build\lib.win32-3.8\twisted\pair
    copying src\twisted\pair\tuntap.py -> build\lib.win32-3.8\twisted\pair
    copying src\twisted\pair\__init__.py -> build\lib.win32-3.8\twisted\pair
    creating build\lib.win32-3.8\twisted\persisted
    copying src\twisted\persisted\aot.py -> build\lib.win32-3.8\twisted\persisted
    copying src\twisted\persisted\crefutil.py -> build\lib.win32-3.8\twisted\persisted
    copying src\twisted\persisted\dirdbm.py -> build\lib.win32-3.8\twisted\persisted
    copying src\twisted\persisted\sob.py -> build\lib.win32-3.8\twisted\persisted
    copying src\twisted\persisted\styles.py -> build\lib.win32-3.8\twisted\persisted
    copying src\twisted\persisted\__init__.py -> build\lib.win32-3.8\twisted\persisted
    creating build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\cred_anonymous.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\cred_file.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\cred_memory.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\cred_sshkeys.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\cred_unix.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_conch.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_core.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_ftp.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_inet.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_names.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_portforward.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_reactors.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_runner.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_socks.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_trial.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_web.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\twisted_words.py -> build\lib.win32-3.8\twisted\plugins
    copying src\twisted\plugins\__init__.py -> build\lib.win32-3.8\twisted\plugins
    creating build\lib.win32-3.8\twisted\positioning
    copying src\twisted\positioning\base.py -> build\lib.win32-3.8\twisted\positioning
    copying src\twisted\positioning\ipositioning.py -> build\lib.win32-3.8\twisted\positioning
    copying src\twisted\positioning\nmea.py -> build\lib.win32-3.8\twisted\positioning
    copying src\twisted\positioning\_sentence.py -> build\lib.win32-3.8\twisted\positioning
    copying src\twisted\positioning\__init__.py -> build\lib.win32-3.8\twisted\positioning
    creating build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\amp.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\basic.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\dict.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\finger.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\ftp.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\htb.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\ident.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\loopback.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\memcache.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\pcp.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\policies.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\portforward.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\postfix.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\sip.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\socks.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\stateful.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\tls.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\wire.py -> build\lib.win32-3.8\twisted\protocols
    copying src\twisted\protocols\__init__.py -> build\lib.win32-3.8\twisted\protocols
    creating build\lib.win32-3.8\twisted\python
    copying src\twisted\python\compat.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\components.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\constants.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\context.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\deprecate.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\failure.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\fakepwd.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\filepath.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\formmethod.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\htmlizer.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\lockfile.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\log.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\logfile.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\modules.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\monkey.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\procutils.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\randbytes.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\rebuild.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\reflect.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\release.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\roots.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\runtime.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\sendmsg.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\shortcut.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\syslog.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\systemd.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\text.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\threadable.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\threadpool.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\url.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\urlpath.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\usage.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\util.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\versions.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\win32.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\zippath.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\zipstream.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_appdirs.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_inotify.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_oldstyle.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_release.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_setup.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_shellcomp.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_textattributes.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_tzhelper.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\_url.py -> build\lib.win32-3.8\twisted\python
    copying src\twisted\python\__init__.py -> build\lib.win32-3.8\twisted\python
    creating build\lib.win32-3.8\twisted\runner
    copying src\twisted\runner\inetd.py -> build\lib.win32-3.8\twisted\runner
    copying src\twisted\runner\inetdconf.py -> build\lib.win32-3.8\twisted\runner
    copying src\twisted\runner\inetdtap.py -> build\lib.win32-3.8\twisted\runner
    copying src\twisted\runner\procmon.py -> build\lib.win32-3.8\twisted\runner
    copying src\twisted\runner\procmontap.py -> build\lib.win32-3.8\twisted\runner
    copying src\twisted\runner\__init__.py -> build\lib.win32-3.8\twisted\runner
    creating build\lib.win32-3.8\twisted\scripts
    copying src\twisted\scripts\htmlizer.py -> build\lib.win32-3.8\twisted\scripts
    copying src\twisted\scripts\trial.py -> build\lib.win32-3.8\twisted\scripts
    copying src\twisted\scripts\twistd.py -> build\lib.win32-3.8\twisted\scripts
    copying src\twisted\scripts\_twistd_unix.py -> build\lib.win32-3.8\twisted\scripts
    copying src\twisted\scripts\_twistw.py -> build\lib.win32-3.8\twisted\scripts
    copying src\twisted\scripts\__init__.py -> build\lib.win32-3.8\twisted\scripts
    creating build\lib.win32-3.8\twisted\spread
    copying src\twisted\spread\banana.py -> build\lib.win32-3.8\twisted\spread
    copying src\twisted\spread\flavors.py -> build\lib.win32-3.8\twisted\spread
    copying src\twisted\spread\interfaces.py -> build\lib.win32-3.8\twisted\spread
    copying src\twisted\spread\jelly.py -> build\lib.win32-3.8\twisted\spread
    copying src\twisted\spread\pb.py -> build\lib.win32-3.8\twisted\spread
    copying src\twisted\spread\publish.py -> build\lib.win32-3.8\twisted\spread
    copying src\twisted\spread\util.py -> build\lib.win32-3.8\twisted\spread
    copying src\twisted\spread\__init__.py -> build\lib.win32-3.8\twisted\spread
    creating build\lib.win32-3.8\twisted\tap
    copying src\twisted\tap\ftp.py -> build\lib.win32-3.8\twisted\tap
    copying src\twisted\tap\portforward.py -> build\lib.win32-3.8\twisted\tap
    copying src\twisted\tap\socks.py -> build\lib.win32-3.8\twisted\tap
    copying src\twisted\tap\__init__.py -> build\lib.win32-3.8\twisted\tap
    creating build\lib.win32-3.8\twisted\test
    copying src\twisted\test\crash_test_dummy.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\iosim.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\mock_win32process.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\myrebuilder1.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\myrebuilder2.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\plugin_basic.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\plugin_extra1.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\plugin_extra2.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_cmdline.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_echoer.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_fds.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_getargv.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_getenv.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_linger.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_reader.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_signal.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_stdinreader.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_tester.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_tty.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\process_twisted.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\proto_helpers.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\reflect_helper_IE.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\reflect_helper_VE.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\reflect_helper_ZDE.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\ssl_helpers.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\stdio_test_consumer.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\stdio_test_halfclose.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\stdio_test_hostpeer.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\stdio_test_lastwrite.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\stdio_test_loseconn.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\stdio_test_producer.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\stdio_test_write.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\stdio_test_writeseq.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\testutils.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_abstract.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_adbapi.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_amp.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_application.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_compat.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_context.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_cooperator.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_defer.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_defgen.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_dict.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_dirdbm.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_error.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_factories.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_failure.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_fdesc.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_finger.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_formmethod.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_ftp.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_ftp_options.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_htb.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_ident.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_internet.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_iosim.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_iutils.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_lockfile.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_log.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_logfile.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_loopback.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_main.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_memcache.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_modules.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_monkey.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_nooldstyle.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_paths.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_pcp.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_persisted.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_plugin.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_policies.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_postfix.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_process.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_protocols.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_randbytes.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_rebuild.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_reflect.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_roots.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_shortcut.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_sip.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_sob.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_socks.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_ssl.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_sslverify.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_stateful.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_stdio.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_strerror.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_strports.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_task.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_tcp.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_tcp_internals.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_text.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_threadable.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_threadpool.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_threads.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_tpfile.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_twistd.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_twisted.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_udp.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_unix.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_usage.py -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\__init__.py -> build\lib.win32-3.8\twisted\test
    creating build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\itrial.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\reporter.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\runner.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\unittest.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\util.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\_asyncrunner.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\_asynctest.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\_synctest.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\__init__.py -> build\lib.win32-3.8\twisted\trial
    copying src\twisted\trial\__main__.py -> build\lib.win32-3.8\twisted\trial
    creating build\lib.win32-3.8\twisted\web
    copying src\twisted\web\client.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\demo.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\distrib.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\domhelpers.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\error.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\guard.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\html.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\http.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\http_headers.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\iweb.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\microdom.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\proxy.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\resource.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\rewrite.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\script.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\server.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\static.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\sux.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\tap.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\template.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\twcgi.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\util.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\vhost.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\wsgi.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\xmlrpc.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\_element.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\_flatten.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\_http2.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\_newclient.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\_responses.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\_stan.py -> build\lib.win32-3.8\twisted\web
    copying src\twisted\web\__init__.py -> build\lib.win32-3.8\twisted\web
    creating build\lib.win32-3.8\twisted\words
    copying src\twisted\words\ewords.py -> build\lib.win32-3.8\twisted\words
    copying src\twisted\words\iwords.py -> build\lib.win32-3.8\twisted\words
    copying src\twisted\words\service.py -> build\lib.win32-3.8\twisted\words
    copying src\twisted\words\tap.py -> build\lib.win32-3.8\twisted\words
    copying src\twisted\words\xmpproutertap.py -> build\lib.win32-3.8\twisted\words
    copying src\twisted\words\__init__.py -> build\lib.win32-3.8\twisted\words
    creating build\lib.win32-3.8\twisted\_threads
    copying src\twisted\_threads\_convenience.py -> build\lib.win32-3.8\twisted\_threads
    copying src\twisted\_threads\_ithreads.py -> build\lib.win32-3.8\twisted\_threads
    copying src\twisted\_threads\_memory.py -> build\lib.win32-3.8\twisted\_threads
    copying src\twisted\_threads\_pool.py -> build\lib.win32-3.8\twisted\_threads
    copying src\twisted\_threads\_team.py -> build\lib.win32-3.8\twisted\_threads
    copying src\twisted\_threads\_threadworker.py -> build\lib.win32-3.8\twisted\_threads
    copying src\twisted\_threads\__init__.py -> build\lib.win32-3.8\twisted\_threads
    creating build\lib.win32-3.8\twisted\application\runner
    copying src\twisted\application\runner\_exit.py -> build\lib.win32-3.8\twisted\application\runner
    copying src\twisted\application\runner\_pidfile.py -> build\lib.win32-3.8\twisted\application\runner
    copying src\twisted\application\runner\_runner.py -> build\lib.win32-3.8\twisted\application\runner
    copying src\twisted\application\runner\__init__.py -> build\lib.win32-3.8\twisted\application\runner
    creating build\lib.win32-3.8\twisted\application\test
    copying src\twisted\application\test\test_internet.py -> build\lib.win32-3.8\twisted\application\test
    copying src\twisted\application\test\test_service.py -> build\lib.win32-3.8\twisted\application\test
    copying src\twisted\application\test\__init__.py -> build\lib.win32-3.8\twisted\application\test
    creating build\lib.win32-3.8\twisted\application\twist
    copying src\twisted\application\twist\_options.py -> build\lib.win32-3.8\twisted\application\twist
    copying src\twisted\application\twist\_twist.py -> build\lib.win32-3.8\twisted\application\twist
    copying src\twisted\application\twist\__init__.py -> build\lib.win32-3.8\twisted\application\twist
    creating build\lib.win32-3.8\twisted\application\runner\test
    copying src\twisted\application\runner\test\test_exit.py -> build\lib.win32-3.8\twisted\application\runner\test
    copying src\twisted\application\runner\test\test_pidfile.py -> build\lib.win32-3.8\twisted\application\runner\test
    copying src\twisted\application\runner\test\test_runner.py -> build\lib.win32-3.8\twisted\application\runner\test
    copying src\twisted\application\runner\test\__init__.py -> build\lib.win32-3.8\twisted\application\runner\test
    creating build\lib.win32-3.8\twisted\application\twist\test
    copying src\twisted\application\twist\test\test_options.py -> build\lib.win32-3.8\twisted\application\twist\test
    copying src\twisted\application\twist\test\test_twist.py -> build\lib.win32-3.8\twisted\application\twist\test
    copying src\twisted\application\twist\test\__init__.py -> build\lib.win32-3.8\twisted\application\twist\test
    creating build\lib.win32-3.8\twisted\conch\client
    copying src\twisted\conch\client\agent.py -> build\lib.win32-3.8\twisted\conch\client
    copying src\twisted\conch\client\connect.py -> build\lib.win32-3.8\twisted\conch\client
    copying src\twisted\conch\client\default.py -> build\lib.win32-3.8\twisted\conch\client
    copying src\twisted\conch\client\direct.py -> build\lib.win32-3.8\twisted\conch\client
    copying src\twisted\conch\client\knownhosts.py -> build\lib.win32-3.8\twisted\conch\client
    copying src\twisted\conch\client\options.py -> build\lib.win32-3.8\twisted\conch\client
    copying src\twisted\conch\client\__init__.py -> build\lib.win32-3.8\twisted\conch\client
    creating build\lib.win32-3.8\twisted\conch\insults
    copying src\twisted\conch\insults\helper.py -> build\lib.win32-3.8\twisted\conch\insults
    copying src\twisted\conch\insults\insults.py -> build\lib.win32-3.8\twisted\conch\insults
    copying src\twisted\conch\insults\text.py -> build\lib.win32-3.8\twisted\conch\insults
    copying src\twisted\conch\insults\window.py -> build\lib.win32-3.8\twisted\conch\insults
    copying src\twisted\conch\insults\__init__.py -> build\lib.win32-3.8\twisted\conch\insults
    creating build\lib.win32-3.8\twisted\conch\openssh_compat
    copying src\twisted\conch\openssh_compat\factory.py -> build\lib.win32-3.8\twisted\conch\openssh_compat
    copying src\twisted\conch\openssh_compat\primes.py -> build\lib.win32-3.8\twisted\conch\openssh_compat
    copying src\twisted\conch\openssh_compat\__init__.py -> build\lib.win32-3.8\twisted\conch\openssh_compat
    creating build\lib.win32-3.8\twisted\conch\scripts
    copying src\twisted\conch\scripts\cftp.py -> build\lib.win32-3.8\twisted\conch\scripts
    copying src\twisted\conch\scripts\ckeygen.py -> build\lib.win32-3.8\twisted\conch\scripts
    copying src\twisted\conch\scripts\conch.py -> build\lib.win32-3.8\twisted\conch\scripts
    copying src\twisted\conch\scripts\tkconch.py -> build\lib.win32-3.8\twisted\conch\scripts
    copying src\twisted\conch\scripts\__init__.py -> build\lib.win32-3.8\twisted\conch\scripts
    creating build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\address.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\agent.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\channel.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\common.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\connection.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\factory.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\filetransfer.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\forwarding.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\keys.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\service.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\session.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\sexpy.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\transport.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\userauth.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\_kex.py -> build\lib.win32-3.8\twisted\conch\ssh
    copying src\twisted\conch\ssh\__init__.py -> build\lib.win32-3.8\twisted\conch\ssh
    creating build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\keydata.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\loopback.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_address.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_agent.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_cftp.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_channel.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_checkers.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_ckeygen.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_conch.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_connection.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_default.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_endpoints.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_filetransfer.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_forwarding.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_helper.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_insults.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_keys.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_knownhosts.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_manhole.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_manhole_tap.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_mixin.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_openssh_compat.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_recvline.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_scripts.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_session.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_ssh.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_tap.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_telnet.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_text.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_transport.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_unix.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_userauth.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\test_window.py -> build\lib.win32-3.8\twisted\conch\test
    copying src\twisted\conch\test\__init__.py -> build\lib.win32-3.8\twisted\conch\test
    creating build\lib.win32-3.8\twisted\conch\ui
    copying src\twisted\conch\ui\ansi.py -> build\lib.win32-3.8\twisted\conch\ui
    copying src\twisted\conch\ui\tkvt100.py -> build\lib.win32-3.8\twisted\conch\ui
    copying src\twisted\conch\ui\__init__.py -> build\lib.win32-3.8\twisted\conch\ui
    creating build\lib.win32-3.8\twisted\cred\test
    copying src\twisted\cred\test\test_cramauth.py -> build\lib.win32-3.8\twisted\cred\test
    copying src\twisted\cred\test\test_cred.py -> build\lib.win32-3.8\twisted\cred\test
    copying src\twisted\cred\test\test_digestauth.py -> build\lib.win32-3.8\twisted\cred\test
    copying src\twisted\cred\test\test_simpleauth.py -> build\lib.win32-3.8\twisted\cred\test
    copying src\twisted\cred\test\test_strcred.py -> build\lib.win32-3.8\twisted\cred\test
    copying src\twisted\cred\test\__init__.py -> build\lib.win32-3.8\twisted\cred\test
    creating build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\iocpreactor\abstract.py -> build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\iocpreactor\const.py -> build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\iocpreactor\interfaces.py -> build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\iocpreactor\reactor.py -> build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\iocpreactor\setup.py -> build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\iocpreactor\tcp.py -> build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\iocpreactor\udp.py -> build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\iocpreactor\__init__.py -> build\lib.win32-3.8\twisted\internet\iocpreactor
    creating build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\connectionmixins.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\fakeendpoint.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\modulehelpers.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\process_cli.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\process_connectionlost.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\process_gireactornocompat.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\process_helper.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\reactormixins.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_abstract.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_address.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_asyncioreactor.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_base.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_baseprocess.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_core.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_coroutines.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_default.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_endpoints.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_epollreactor.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_error.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_fdset.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_filedescriptor.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_gireactor.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_glibbase.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_inlinecb.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_inotify.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_iocp.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_kqueuereactor.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_main.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_newtls.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_pollingfile.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_posixbase.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_posixprocess.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_process.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_protocol.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_resolver.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_serialport.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_sigchld.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_socket.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_stdio.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_tcp.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_testing.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_threads.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_time.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_tls.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_udp.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_udp_internals.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_unix.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_win32events.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\test_win32serialport.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\_posixifaces.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\_win32ifaces.py -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\__init__.py -> build\lib.win32-3.8\twisted\internet\test
    creating build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_buffer.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_capture.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_file.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_filter.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_flatten.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_format.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_global.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_io.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_json.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_legacy.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_levels.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_logger.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_observer.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_stdlib.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\test_util.py -> build\lib.win32-3.8\twisted\logger\test
    copying src\twisted\logger\test\__init__.py -> build\lib.win32-3.8\twisted\logger\test
    creating build\lib.win32-3.8\twisted\mail\scripts
    copying src\twisted\mail\scripts\mailmail.py -> build\lib.win32-3.8\twisted\mail\scripts
    creating build\lib.win32-3.8\twisted\mail\test
    copying src\twisted\mail\test\pop3testserver.py -> build\lib.win32-3.8\twisted\mail\test
    copying src\twisted\mail\test\test_imap.py -> build\lib.win32-3.8\twisted\mail\test
    copying src\twisted\mail\test\test_mailmail.py -> build\lib.win32-3.8\twisted\mail\test
    copying src\twisted\mail\test\test_pop3.py -> build\lib.win32-3.8\twisted\mail\test
    copying src\twisted\mail\test\test_pop3client.py -> build\lib.win32-3.8\twisted\mail\test
    copying src\twisted\mail\test\test_smtp.py -> build\lib.win32-3.8\twisted\mail\test
    copying src\twisted\mail\test\__init__.py -> build\lib.win32-3.8\twisted\mail\test
    creating build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_cache.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_client.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_common.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_dns.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_examples.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_hosts.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_names.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_resolve.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_rfc1982.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_rootresolve.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_server.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_srvconnect.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_tap.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\test_util.py -> build\lib.win32-3.8\twisted\names\test
    copying src\twisted\names\test\__init__.py -> build\lib.win32-3.8\twisted\names\test
    creating build\lib.win32-3.8\twisted\pair\test
    copying src\twisted\pair\test\test_ethernet.py -> build\lib.win32-3.8\twisted\pair\test
    copying src\twisted\pair\test\test_ip.py -> build\lib.win32-3.8\twisted\pair\test
    copying src\twisted\pair\test\test_rawudp.py -> build\lib.win32-3.8\twisted\pair\test
    copying src\twisted\pair\test\test_tuntap.py -> build\lib.win32-3.8\twisted\pair\test
    copying src\twisted\pair\test\__init__.py -> build\lib.win32-3.8\twisted\pair\test
    creating build\lib.win32-3.8\twisted\persisted\test
    copying src\twisted\persisted\test\test_styles.py -> build\lib.win32-3.8\twisted\persisted\test
    copying src\twisted\persisted\test\__init__.py -> build\lib.win32-3.8\twisted\persisted\test
    creating build\lib.win32-3.8\twisted\positioning\test
    copying src\twisted\positioning\test\receiver.py -> build\lib.win32-3.8\twisted\positioning\test
    copying src\twisted\positioning\test\test_base.py -> build\lib.win32-3.8\twisted\positioning\test
    copying src\twisted\positioning\test\test_nmea.py -> build\lib.win32-3.8\twisted\positioning\test
    copying src\twisted\positioning\test\test_sentence.py -> build\lib.win32-3.8\twisted\positioning\test
    copying src\twisted\positioning\test\__init__.py -> build\lib.win32-3.8\twisted\positioning\test
    creating build\lib.win32-3.8\twisted\protocols\haproxy
    copying src\twisted\protocols\haproxy\_exceptions.py -> build\lib.win32-3.8\twisted\protocols\haproxy
    copying src\twisted\protocols\haproxy\_info.py -> build\lib.win32-3.8\twisted\protocols\haproxy
    copying src\twisted\protocols\haproxy\_interfaces.py -> build\lib.win32-3.8\twisted\protocols\haproxy
    copying src\twisted\protocols\haproxy\_parser.py -> build\lib.win32-3.8\twisted\protocols\haproxy
    copying src\twisted\protocols\haproxy\_v1parser.py -> build\lib.win32-3.8\twisted\protocols\haproxy
    copying src\twisted\protocols\haproxy\_v2parser.py -> build\lib.win32-3.8\twisted\protocols\haproxy
    copying src\twisted\protocols\haproxy\_wrapper.py -> build\lib.win32-3.8\twisted\protocols\haproxy
    copying src\twisted\protocols\haproxy\__init__.py -> build\lib.win32-3.8\twisted\protocols\haproxy
    creating build\lib.win32-3.8\twisted\protocols\test
    copying src\twisted\protocols\test\test_basic.py -> build\lib.win32-3.8\twisted\protocols\test
    copying src\twisted\protocols\test\test_tls.py -> build\lib.win32-3.8\twisted\protocols\test
    copying src\twisted\protocols\test\__init__.py -> build\lib.win32-3.8\twisted\protocols\test
    creating build\lib.win32-3.8\twisted\protocols\haproxy\test
    copying src\twisted\protocols\haproxy\test\test_parser.py -> build\lib.win32-3.8\twisted\protocols\haproxy\test
    copying src\twisted\protocols\haproxy\test\test_v1parser.py -> build\lib.win32-3.8\twisted\protocols\haproxy\test
    copying src\twisted\protocols\haproxy\test\test_v2parser.py -> build\lib.win32-3.8\twisted\protocols\haproxy\test
    copying src\twisted\protocols\haproxy\test\test_wrapper.py -> build\lib.win32-3.8\twisted\protocols\haproxy\test
    copying src\twisted\protocols\haproxy\test\__init__.py -> build\lib.win32-3.8\twisted\protocols\haproxy\test
    creating build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\deprecatedattributes.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\modules_helpers.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\pullpipe.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_appdirs.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_components.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_constants.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_deprecate.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_dist3.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_fakepwd.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_htmlizer.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_inotify.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_release.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_runtime.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_sendmsg.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_setup.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_shellcomp.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_syslog.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_systemd.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_textattributes.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_tzhelper.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_url.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_urlpath.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_util.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_versions.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_zippath.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\test_zipstream.py -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\python\test\__init__.py -> build\lib.win32-3.8\twisted\python\test
    creating build\lib.win32-3.8\twisted\runner\test
    copying src\twisted\runner\test\test_inetdconf.py -> build\lib.win32-3.8\twisted\runner\test
    copying src\twisted\runner\test\test_procmon.py -> build\lib.win32-3.8\twisted\runner\test
    copying src\twisted\runner\test\test_procmontap.py -> build\lib.win32-3.8\twisted\runner\test
    copying src\twisted\runner\test\__init__.py -> build\lib.win32-3.8\twisted\runner\test
    creating build\lib.win32-3.8\twisted\scripts\test
    copying src\twisted\scripts\test\test_scripts.py -> build\lib.win32-3.8\twisted\scripts\test
    copying src\twisted\scripts\test\__init__.py -> build\lib.win32-3.8\twisted\scripts\test
    creating build\lib.win32-3.8\twisted\spread\test
    copying src\twisted\spread\test\test_banana.py -> build\lib.win32-3.8\twisted\spread\test
    copying src\twisted\spread\test\test_jelly.py -> build\lib.win32-3.8\twisted\spread\test
    copying src\twisted\spread\test\test_pb.py -> build\lib.win32-3.8\twisted\spread\test
    copying src\twisted\spread\test\test_pbfailure.py -> build\lib.win32-3.8\twisted\spread\test
    copying src\twisted\spread\test\__init__.py -> build\lib.win32-3.8\twisted\spread\test
    creating build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\detests.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\erroneous.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\mockcustomsuite.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\mockcustomsuite2.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\mockcustomsuite3.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\mockdoctest.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\moduleself.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\moduletest.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\novars.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\ordertests.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\packages.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\sample.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\scripttest.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\skipping.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\suppression.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_assertions.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_asyncassertions.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_deferred.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_doctest.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_keyboard.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_loader.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_log.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_output.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_plugins.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_pyunitcompat.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_reporter.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_runner.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_script.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_suppression.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_testcase.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_tests.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_util.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\test_warning.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\weird.py -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\trial\test\__init__.py -> build\lib.win32-3.8\twisted\trial\test
    creating build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\distreporter.py -> build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\disttrial.py -> build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\managercommands.py -> build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\options.py -> build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\worker.py -> build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\workercommands.py -> build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\workerreporter.py -> build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\workertrial.py -> build\lib.win32-3.8\twisted\trial\_dist
    copying src\twisted\trial\_dist\__init__.py -> build\lib.win32-3.8\twisted\trial\_dist
    creating build\lib.win32-3.8\twisted\trial\_dist\test
    copying src\twisted\trial\_dist\test\test_distreporter.py -> build\lib.win32-3.8\twisted\trial\_dist\test
    copying src\twisted\trial\_dist\test\test_disttrial.py -> build\lib.win32-3.8\twisted\trial\_dist\test
    copying src\twisted\trial\_dist\test\test_options.py -> build\lib.win32-3.8\twisted\trial\_dist\test
    copying src\twisted\trial\_dist\test\test_worker.py -> build\lib.win32-3.8\twisted\trial\_dist\test
    copying src\twisted\trial\_dist\test\test_workerreporter.py -> build\lib.win32-3.8\twisted\trial\_dist\test
    copying src\twisted\trial\_dist\test\test_workertrial.py -> build\lib.win32-3.8\twisted\trial\_dist\test
    copying src\twisted\trial\_dist\test\__init__.py -> build\lib.win32-3.8\twisted\trial\_dist\test
    creating build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\injectionhelpers.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\requesthelper.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_agent.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_cgi.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_client.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_distrib.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_domhelpers.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_error.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_flatten.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_html.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_http.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_http2.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_httpauth.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_http_headers.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_newclient.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_proxy.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_resource.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_script.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_stan.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_static.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_tap.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_template.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_util.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_vhost.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_web.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_webclient.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_web__responses.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_wsgi.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_xml.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\test_xmlrpc.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\_util.py -> build\lib.win32-3.8\twisted\web\test
    copying src\twisted\web\test\__init__.py -> build\lib.win32-3.8\twisted\web\test
    creating build\lib.win32-3.8\twisted\web\_auth
    copying src\twisted\web\_auth\basic.py -> build\lib.win32-3.8\twisted\web\_auth
    copying src\twisted\web\_auth\digest.py -> build\lib.win32-3.8\twisted\web\_auth
    copying src\twisted\web\_auth\wrapper.py -> build\lib.win32-3.8\twisted\web\_auth
    copying src\twisted\web\_auth\__init__.py -> build\lib.win32-3.8\twisted\web\_auth
    creating build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\im\baseaccount.py -> build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\im\basechat.py -> build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\im\basesupport.py -> build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\im\interfaces.py -> build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\im\ircsupport.py -> build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\im\locals.py -> build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\im\pbsupport.py -> build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\im\__init__.py -> build\lib.win32-3.8\twisted\words\im
    creating build\lib.win32-3.8\twisted\words\protocols
    copying src\twisted\words\protocols\irc.py -> build\lib.win32-3.8\twisted\words\protocols
    copying src\twisted\words\protocols\__init__.py -> build\lib.win32-3.8\twisted\words\protocols
    creating build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_basechat.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_basesupport.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_domish.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_irc.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_ircsupport.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_irc_service.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabberclient.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabbercomponent.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabbererror.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabberjid.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabberjstrports.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabbersasl.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabbersaslmechanisms.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabberxmlstream.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_jabberxmppstringprep.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_service.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_tap.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_xishutil.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_xmlstream.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_xmpproutertap.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\test_xpath.py -> build\lib.win32-3.8\twisted\words\test
    copying src\twisted\words\test\__init__.py -> build\lib.win32-3.8\twisted\words\test
    creating build\lib.win32-3.8\twisted\words\xish
    copying src\twisted\words\xish\domish.py -> build\lib.win32-3.8\twisted\words\xish
    copying src\twisted\words\xish\utility.py -> build\lib.win32-3.8\twisted\words\xish
    copying src\twisted\words\xish\xmlstream.py -> build\lib.win32-3.8\twisted\words\xish
    copying src\twisted\words\xish\xpath.py -> build\lib.win32-3.8\twisted\words\xish
    copying src\twisted\words\xish\xpathparser.py -> build\lib.win32-3.8\twisted\words\xish
    copying src\twisted\words\xish\__init__.py -> build\lib.win32-3.8\twisted\words\xish
    creating build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\client.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\component.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\error.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\ijabber.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\jid.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\jstrports.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\sasl.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\sasl_mechanisms.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\xmlstream.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\xmpp_stringprep.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    copying src\twisted\words\protocols\jabber\__init__.py -> build\lib.win32-3.8\twisted\words\protocols\jabber
    creating build\lib.win32-3.8\twisted\_threads\test
    copying src\twisted\_threads\test\test_convenience.py -> build\lib.win32-3.8\twisted\_threads\test
    copying src\twisted\_threads\test\test_memory.py -> build\lib.win32-3.8\twisted\_threads\test
    copying src\twisted\_threads\test\test_team.py -> build\lib.win32-3.8\twisted\_threads\test
    copying src\twisted\_threads\test\test_threadworker.py -> build\lib.win32-3.8\twisted\_threads\test
    copying src\twisted\_threads\test\__init__.py -> build\lib.win32-3.8\twisted\_threads\test
    running egg_info
    writing src\Twisted.egg-info\PKG-INFO
    writing dependency_links to src\Twisted.egg-info\dependency_links.txt
    writing entry points to src\Twisted.egg-info\entry_points.txt
    writing requirements to src\Twisted.egg-info\requires.txt
    writing top-level names to src\Twisted.egg-info\top_level.txt
    reading manifest file 'src\Twisted.egg-info\SOURCES.txt'
    reading manifest template 'MANIFEST.in'
    warning: no previously-included files matching '*.misc' found under directory 'src\twisted'
    warning: no previously-included files matching '*.bugfix' found under directory 'src\twisted'
    warning: no previously-included files matching '*.doc' found under directory 'src\twisted'
    warning: no previously-included files matching '*.feature' found under directory 'src\twisted'
    warning: no previously-included files matching '*.removal' found under directory 'src\twisted'
    warning: no previously-included files matching 'NEWS' found under directory 'src\twisted'
    warning: no previously-included files matching 'README' found under directory 'src\twisted'
    warning: no previously-included files matching 'newsfragments' found under directory 'src\twisted'
    warning: no previously-included files found matching 'src\twisted\topfiles\CREDITS'
    warning: no previously-included files found matching 'src\twisted\topfiles\ChangeLog.Old'
    warning: no previously-included files found matching 'pyproject.toml'
    warning: no previously-included files found matching 'codecov.yml'
    warning: no previously-included files found matching 'appveyor.yml'
    warning: no previously-included files found matching '.coveralls.yml'
    warning: no previously-included files found matching '.circleci'
    warning: no previously-included files matching '*' found under directory '.circleci'
    no previously-included directories found matching 'bin'
    no previously-included directories found matching 'admin'
    no previously-included directories found matching '.travis'
    no previously-included directories found matching '.github'
    warning: no previously-included files found matching 'docs\historic\2003'
    warning: no previously-included files matching '*' found under directory 'docs\historic\2003'
    writing manifest file 'src\Twisted.egg-info\SOURCES.txt'
    copying src\twisted\python\twisted-completion.zsh -> build\lib.win32-3.8\twisted\python
    creating build\lib.win32-3.8\twisted\python\_pydoctortemplates
    copying src\twisted\python\_pydoctortemplates\common.html -> build\lib.win32-3.8\twisted\python\_pydoctortemplates
    copying src\twisted\python\_pydoctortemplates\index.html -> build\lib.win32-3.8\twisted\python\_pydoctortemplates
    copying src\twisted\python\_pydoctortemplates\summary.html -> build\lib.win32-3.8\twisted\python\_pydoctortemplates
    copying src\twisted\test\cert.pem.no_trailing_newline -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\key.pem.no_trailing_newline -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\server.pem -> build\lib.win32-3.8\twisted\test
    copying src\twisted\test\test_defer.py.3only -> build\lib.win32-3.8\twisted\test
    copying src\twisted\internet\iocpreactor\notes.txt -> build\lib.win32-3.8\twisted\internet\iocpreactor
    copying src\twisted\internet\test\_awaittests.py.3only -> build\lib.win32-3.8\twisted\internet\test
    copying src\twisted\internet\test\_yieldfromtests.py.3only -> build\lib.win32-3.8\twisted\internet\test
    creating build\lib.win32-3.8\twisted\internet\test\fake_CAs
    copying src\twisted\internet\test\fake_CAs\chain.pem -> build\lib.win32-3.8\twisted\internet\test\fake_CAs
    copying src\twisted\internet\test\fake_CAs\not-a-certificate -> build\lib.win32-3.8\twisted\internet\test\fake_CAs
    copying src\twisted\internet\test\fake_CAs\thing1.pem -> build\lib.win32-3.8\twisted\internet\test\fake_CAs
    copying src\twisted\internet\test\fake_CAs\thing2-duplicate.pem -> build\lib.win32-3.8\twisted\internet\test\fake_CAs
    copying src\twisted\internet\test\fake_CAs\thing2.pem -> build\lib.win32-3.8\twisted\internet\test\fake_CAs
    copying src\twisted\mail\test\rfc822.message -> build\lib.win32-3.8\twisted\mail\test
    copying src\twisted\python\test\_deprecatetests.py.3only -> build\lib.win32-3.8\twisted\python\test
    copying src\twisted\trial\test\_assertiontests.py.3only -> build\lib.win32-3.8\twisted\trial\test
    copying src\twisted\words\im\instancemessenger.glade -> build\lib.win32-3.8\twisted\words\im
    copying src\twisted\words\xish\xpathparser.g -> build\lib.win32-3.8\twisted\words\xish
    running build_ext
    building 'twisted.test.raiser' extension
    error: Microsoft Visual C++ 14.0 is required. Get it with "Microsoft Visual C++ Build Tools": https://visualstudio.microsoft.com/downloads/
    ----------------------------------------
ERROR: Command errored out with exit status 1: 'c:\users\david\appdata\local\programs\python\python38-32\python.exe' -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\David\\AppData\\Local\\Temp\\pip-install-dcegoj9r\\Twisted\\setup.py'"'"'; __file__='"'"'C:\\Users\\David\\AppData\\Local\\Temp\\pip-install-dcegoj9r\\Twisted\\setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\David\AppData\Local\Temp\pip-record-8yygxett\install-record.txt' --single-version-externally-managed --compile --install-headers 'c:\users\david\appdata\local\programs\python\python38-32\Include\Twisted' Check the logs for full command output.
