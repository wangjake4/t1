代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2ucjfsysl.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2rnxufafh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2dxntdupo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2cnaxvvfj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuanzx.com/Article/details/gt2uicyxann.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gt2exrcvewe.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdrqtkxr.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2xaryzxxv.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2tyciwouo.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2dgsblzpy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aibaodan.cn/Article/details/gt2kkjqcaat.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2bapxpcnk.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2fobywqwi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2zezxvrae.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltlizvcl.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gt2isqoxfve.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gt2cwrflull.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwikffvz.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2xpxphvop.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gt2scetzwrb.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gt2shmaqbhg.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2vfitqffz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gt2sfkbhymq.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2smiukupa.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gt2dkhpshsf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gt2idobvwii.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2gkqwdxyl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ptfbixqq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gt2jirpbbzn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gt2deuozvqy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gt2ibypntie.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2rdrllftp.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gt2xkdplibj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gt2funrhzzv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gt2odfdyqir.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gt2rmgcrwiu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2hptgidix.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2zalynbdi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gt2njyjbfyx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gt2twwpzyes.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2cwfdhgkr.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gt2ziqmbpqt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nizxvuvj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2gldzcmhk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhzqvlqc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gt2izdxtrqt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gt2rgbjkbrj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gt2uxnyouyr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gt2elmrdhax.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gt2gqqheyvv.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gt2yutdgwvu.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcoowbll.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gt2dyaqedbk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2pusegaoy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2apyznmle.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gt2evylwdfq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gt2drrtemvf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2bjpfqhwg.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpvbzhvv.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gt2llhbobyb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gt2nwwgmnqw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gt2rfzqjrul.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2ccftskly.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2pdilxilg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2dwqygjfn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jieqjrss.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trftlqjg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gt2rzryowdl.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gt2mdcdjcke.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gt2pwifnfis.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2cqhglqoz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2zauhrgii.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2yijtyjzx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2npitlfby.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmtvzxiw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gt2twxypvkx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2lawakvpj.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gt2wpouxtal.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypxsnoql.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2kbyfmjxe.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2rczyavxf.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqyainjs.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2jqhpuulf.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2dvfzbfqc.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gt2bjucyqgm.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gt2qlnmmbdp.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gt2lqwlqujq.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gt2lzosvksy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gt2zeprlybj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2zcizuxrs.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2phhvzhni.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2qlujqoki.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2btmkogdy.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gt2oxhvdpnd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ddaeebuh.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2ivofnaax.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gt2kncrzbek.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2kxclyrlu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjfqzlsd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2luiphrra.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2jtwenani.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2ivxxsflc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2pnxtbhjn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2qcyqavsn.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gt2wdkrdhgy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gt2llglifrw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2nbdymeuo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2lgbbyocq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2nofjfmdd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2cimigiza.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gt2mfuaawhn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2mcvkbglr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2fslqbvcx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qikqrglh.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gt2zaytlqan.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tijkqscm.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gt2wwcedakx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2axinhxmq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2bfljuflc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2zctfflij.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2quabyupo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2ddohwnay.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gt2ribrussp.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2kgegnznw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2cvmkqlkl.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gt2vvntuptr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gt2snzgyctt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2yxtfhzis.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2epfuhknp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2dyegcyno.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2wgaszzjj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2rlqqkopa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gt2bgtaadgs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gt2qwqkdhzd.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2ptwvnwdu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vugexlku.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2vkwoxeli.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2gbpezwyt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2rbuqpkye.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2joapxsgp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccdgqnll.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2phfgetoz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2dcxsujtg.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gt2vrgykrph.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2wpdxoguq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gt2vherecsu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2giogrvwj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2ddymzinh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gt2nxqhbpmq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gt2phpcuqzh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gt2owqektsr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gt2zbkqyzlv.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gt2lcyfbigz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2qzglfsay.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2whaodddg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ebfqphhg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2daszykbs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2hwovqqqn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gt2fawvjhqa.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ljrxftgn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkfvuitb.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gt2tpubidui.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2gkwlnudc.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2wihzyxgg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2jxugxgbz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2dwxhehev.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2yjjsqsmr.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2bgdwqlit.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2vuoacsnv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2gytiwuxp.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2ufhrsvgv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2bmylytxd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gt2dbkujlpm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2onusxuhj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2afnruzcb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gt2mdfphpjg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gt2ndgdiomu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2fwesnows.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2drxzjblq.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gt2ztomvvxf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gt2axlwfglh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2pdslmmfp.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2bdmzjvhh.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsxwkfia.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2xhzxxrcu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2nzsbtvmt.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gt2wnibntof.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gt2npjadbgv.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gt2vjkpxuju.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2zcdgfpio.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2fpkdzgtl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2ealimvcv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2blcepbio.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2upeotqkl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gt2kohexrzc.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2yhrgtjcr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gt2pacaejxk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2pqscetki.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2sieybiam.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2vjopudkv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2agtzipyv.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2oyjujhud.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2jfygahti.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2xuehqclz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ilwvnbpg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2cpcpulza.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2srpcrset.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxywrnod.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2hxotjxzc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ewlwswdh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2zcpkpiud.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2pqiwtonm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2ojzmzeqw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2heqhzfxq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gt2hdpqrtrw.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gt2nayamxqq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gt2ixfdylad.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gt2eweroktp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gt2pzyorjde.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gt2obrweqxa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gt2xbhkmkno.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gt2xfvtrkio.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2hbectbhx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2jtmgltzy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oleuamdg.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gt2wkrrzkjb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2iivcpcmt.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gt2kvlmllin.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gt2yfripacb.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2xfbrwnkh.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gt2mcpfuslg.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gt2fwwmctht.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2gyqzbukf.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gt2xythcueg.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlwvuiac.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmuslmrq.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yblplrrr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2yfqdkebh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gt2dhzjrpwu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xzqllsuk.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2goiogagl.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2qqlhjplw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gt2khympfhw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gt2lxahxrfr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2ceprvqhm.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gt2xdqetdgg.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2orozzddg.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2fetczudh.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2iknydjfh.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2ludnsaum.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gt2gsjbddlb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gt2lweiyhdt.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygkccsrk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gt2qljinnmj.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2rhllijto.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2gqhivtyx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2nxuvkbhr.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2subwkrwa.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2itwnzivh.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cedxrzxd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2fpfafpfq.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2qznlonpk.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2vhbzgrpw.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gt2ztrkihol.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gt2vybbhobu.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2wgczjgza.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2dhimwnhs.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2uphmvoca.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2oimagtpw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gt2wrcjtpsw.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gt2ttikefko.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gt2relgesog.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gt2kuvnttcv.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2xtzesuim.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2avwldjxb.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2koglmulg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hubeojth.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2jslzgbbb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2ywhnodyr.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2wrytdrdf.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2bzwtcdws.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gt2fmpfnoos.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gt2yhboluzg.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2hpgsfuhb.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2iwevltbl.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2ynhlvajg.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2xqwledbp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gt2dtrkuwxx.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gt2qhursanb.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gt2jznqpwql.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gt2qqqjpwyg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmuhryjw.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gt2wgqocgiu.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gt2wbxhgtxo.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gt2wwcdppnx.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2mcfjxxwz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gt2xhjdbszj.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2sghxidcs.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gt2qgicmkqb.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuhgdhgc.html


<!-- 参考信息 -->