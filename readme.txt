 *   Argos
 *   Copyright (c) Stuart Halloway. All rights reserved.
 *   The use and distribution terms for this software are covered by the
 *   Eclipse Public License 1.0 (http://opensource.org/licenses/eclipse-1.0.php)
 *   which can be found in the file epl-v10.html at the root of this distribution.
 *   By using this software in any fashion, you are agreeing to be bound by
 * 	 the terms of this license.
 *   You must not remove this notice, or any other, from this software.

Argos tests how your local copy of Clojure and Contrib works with a
bunch of different open-source libraries. Used as a sanity check for
changes to Clojure and Contrib itself.

One-time setup:

(1) Set CLOJURE_HOME to your local Clojure build. Contrib must be in a
directory at the same level.

(2) script/setup clones a bunch of git repos to the work directory

Use:

(1) Make sure your Clojure and Contrib are built.

(2) script/test-* tests a library, script/test-all tests them all.

