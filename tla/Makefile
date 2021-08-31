run: run-not-fixed run-fixed

run-not-fixed:
	cd bug-not-fixed && python3 ../../deps/tlc-cmd/tlcwrapper.py config.ini

run-fixed:
	cd bug-fixed && python3 ../../deps/tlc-cmd/tlcwrapper.py config.ini

clean:
	find . -maxdepth 2 -type d -name batch\* -exec rm -rf '{}' +
	rm -rf MC_summary*
