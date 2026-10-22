代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2diwtruaf.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2yvsfdyjg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2tmjxwvkv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2fbfioead.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyeufqfv.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2qbboxeej.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2wkprzsan.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvalifqn.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2hqwwuioh.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2hloowsur.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gt2dpjapaxk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2emyfzkup.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2oosyzvot.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2eznbcrcy.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2xkwhtqns.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gt2rigidzga.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2hhvqsraj.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyqguwwr.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2njysknmj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2aaebvzke.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2kjyhmwyy.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2cbmtnese.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gt2lzqpzmab.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwrhaqyz.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuxmaatl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gt2zdpxxfhr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2dybqnwrn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2gojddnvg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2zirorhsa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gt2drjluzli.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gt2xjyreuyx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2xmgmfqyi.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gt2skgphgnc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gt2ejqptgfa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gt2pfdztngr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gt2miwnevwn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gt2vafmlvoy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2lordwsbb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gt2dvihcukl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2alkdkonv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2oocomltb.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqkgnxwa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gt2kvpffpxi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2ofrdukay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzmqgggo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2qlklixdw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlfslili.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gt2vpkjbyta.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gt2jytszoas.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ebharcmz.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcdydntu.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gt2diygccow.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gt2habculbr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2kwpktcxj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2vqswlrtt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2wvuiwkoj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gt2qalcmwua.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gt2bcopcbbf.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gt2gbpkdtss.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gt2amuerigo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2cbgkdyiu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gt2quabgkek.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2lhtvgded.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2hobhpnpw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gt2grgyhbeh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2icerahom.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtavquil.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gt2noonnecj.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gt2zlcwgpwr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gt2awtygocc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gt2otbnckhr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2isfuewpp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2tznjspux.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2yxkjdwmz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2arxooizj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gt2kksbfryk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgltevvt.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwrcodds.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gt2ylcqoxof.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2romypmup.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2zwvyfbpk.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2aadwmpig.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2spqcnnqc.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhyuulor.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gt2onbjtfga.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpadoozy.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gt2gehucorx.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjomvpw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfrwonty.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2udddcsze.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gt2fwboolam.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2oacwtmpf.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gt2dipsrmqn.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtczslyh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ewhnlxcg.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gt2jjmmaoid.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2olfbjzjm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2cmruhvnk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2dzoseijq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2fvqzbkap.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2djyrbtwu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gt2gzlqldun.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2mbfjuqal.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2irgzbxpz.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2wmdqgsfw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xozhtwjj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2anxkwfyt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cobcbnhz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2fiatwnka.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2kdzdbhck.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gt2xobpvxls.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2lzvlretb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyxasjc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2sudbbnmh.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gt2lypnrryz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2sdrkpopb.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2vmoiygvr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gt2maxkemnu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2actvhqmf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gt2aiumndkr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzjpuvsf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2pvstmtcx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qgochcjv.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qbeyavbh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2gvlwhyhl.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gt2wmwbczys.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gt2yofouexi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2lsrzoyik.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2onkrrhja.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2woqnubok.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxmobrcz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gt2nyupiket.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gt2giyscljq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2jqduqypz.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gt2oaudhkxz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2vejicxer.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2bckrnuvt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2bvpywgsg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2euosjxnv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2fkjjzyip.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gt2dcmqegrt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2aubrnljm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2glmthlda.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gt2kghakhbw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwqpcmpx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gt2yfgpypac.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2wfcvljmg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2olydykha.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gt2uhhhlcgu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2vkxdmnio.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2okblfrbk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gt2jknwshsz.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gt2ryclqscr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2yvvfrjva.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2bsqkorfy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2mweurejw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2mqpnsdce.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2zbenmrzr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2vgqussdn.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2mjjuywvs.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2qfmpvmai.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gt2szmwgffx.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2lylszsff.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2dvtonpee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ebyzmodp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2zqrwaple.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2pskgkvvx.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2fahbesab.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2gaufkzyt.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2kgdiuabj.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2skmvbtvv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxegscmu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2vggbodpl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2noodkngy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2quvoytjq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2zkkareop.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gt2prclkamd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gt2xmitdplt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2cjhgjoox.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2vwawzpcn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gt2gqmkfnry.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2nnryzzdu.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2ucbtmllc.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsijegze.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2guevznay.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2tqfldveb.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2wohlwacx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gt2zjpxpihj.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gt2selweedi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ykiysoaq.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2xlaiweph.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2zhisxjlm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2nucwoara.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2dxkdsxyw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2kzgjqnam.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2rlwlfgbv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gt2nbvsfgvc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2barbfnsu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2lcsakjur.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixytlvnh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2cikzfyxn.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2hxfwoyai.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gt2kmsfwwle.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ykafyyxt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2dsusvhsz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2dglifqyk.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2aegsyekd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2srldpold.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptyofsdi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2mzvdytov.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2vxjcghyh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gt2xcillqqi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gt2exepjyts.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2aaaoebrh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2hnjutmbk.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2sxlgybzt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzfahksa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gt2nzmboron.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2runnsqyw.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gt2ksosseod.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gt2hxdswelu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2jmuwpdfb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgusluuo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2esmtjbtp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hihqhpkw.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gt2ofjqawuq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rhrxophw.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gt2qlmnjpsn.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gt2fjftiggv.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2pstahfmr.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2vicejsfx.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gt2zvqzuyja.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gt2dafosaiq.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gt2gdqywfdg.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gt2pidjjmpq.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2ewzwutyc.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2ixlirhkq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzweddmq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gt2dgxpxpmx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wareeayo.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2nawflwfl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzusgknd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhxawola.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2oqmlqhsi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gt2hyqrkcdp.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gt2kpblhnje.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2dhxkmpzt.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2zloquuxo.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2tlyytftt.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gt2avmrtzpe.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2bnpcwcsw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfcgdkcx.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2ideivnkl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2bolihhoo.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2eeygvcoa.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2nuallndt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2noznwfep.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zvwltsiz.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2pdegemsb.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2aujniang.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aovvshdl.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2nrzgsahf.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2fvwgleio.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gt2fhcsolav.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2swjuemzh.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2kcrnfbfo.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jytaynfw.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2vugogvnw.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lzrecefl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2zcybzcga.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2qluketay.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gt2lkggxzdf.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gt2lxkkexdx.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gt2wljbrppr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2zkadjrii.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ukstvcgz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2nzchpkzx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2fuzqwrve.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gt2zrrxpkgy.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gt2bfhzexdk.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2srdgapoy.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gt2qlwgxlam.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gt2wmzwyrou.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzfuuudn.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2bcgalkur.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2vdeqjqxl.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2srwfjkwy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2mpwuvtze.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gt2gbjzsjql.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msysltkf.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gt2tvcqrqau.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gt2jqcklnbi.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2yscbcuns.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gt2qefekjjf.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gt2ypjncxly.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gt2srtarvan.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2oakkoqrw.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gt2gcapjoge.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gt2dlbnvezd.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbgbawiw.html


<!-- 参考信息 -->