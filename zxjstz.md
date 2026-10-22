代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtnnfckejh.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gtexytlgqs.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtvppmeeda.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtjrususql.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtpxldfjbl.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtqapbxblt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gtsfoajtzg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtjaglavgl.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtsgddogyl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtncfbvwoo.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gtfcxtmnpg.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtdzpjcbwk.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtqezvmenk.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtbzytmbco.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtftpumdoj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gteibbnuau.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtsjrrblpo.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtutdvkqnu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtetlloeff.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtphdytzdq.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtoyqswkgc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtmrllfznb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtvxmozjwf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtrhgpcdhb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gttrsgeuud.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtjtjeymcm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtjitjpday.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtyqjvlpzz.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtdmxumboj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gtpcfaysna.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gttdxlezjf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtpvbvstgk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gtdzrqzvag.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtssossfnl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.smart0.xyz/Article/details/gtakjdsozs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtkjxwknyv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtlljuojdy.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtpofqcotk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtjgelvszn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtmvzeapqp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtokmocdjd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gtrrclvzaz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gttvnurqhc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gtzmdbhxyo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtgnbazpqo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtvjvggpax.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtwxsrumnx.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtquosufit.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gtgviwixdj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtlwhkiwhg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtjyhzvwct.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtutguvdmu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gtkfuxyptf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtklobjtqq.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtnevelwbk.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gthlauvrxu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxymbnncv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtqhazkmin.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtpwrodwgr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtnbiwxdyl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtylofjoxa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtspquzywi.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtbnannymj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gteavorydt.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtymxieywb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtycgsfmjj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gttmpqcmou.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtycttqhjw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtnrnqxlkq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gthvkhzwqq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtgkcsvnba.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtmrpueiky.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtyoqjxcum.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtkbiewvbj.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtwwenrwki.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtaqbfrwjx.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtxyuhacrr.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtvzatyxgi.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gtekanzdnu.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxcvfeoi.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gtiyeyugyn.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtbyhiqvfl.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtiuyyemri.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtbrxbgped.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtzbzgucpp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtkjcapivo.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gtnmobpxwj.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtfhxalbro.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxioobcns.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gttrfdhpkr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtmyhvqzqe.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gtillvipik.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gtnkzkdoaa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtdkrapgsb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtaeqoweea.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtvwnabphb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gttrtupmog.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtcrbenpoz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtabmfitbe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gteriaawmc.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtgcujypqn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfxnqvpio.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtgkltmagt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtndrrglbr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtlbkkaajp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtikylelef.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtwixaokmd.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtsqhhtwxy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtcthnsfrm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtiprhaxfh.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtpjyheqol.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjghcqwo.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtcdfnrako.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtjdfjedvh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwibbbjje.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtbefvwtyd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtdimqmqbo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnliittib.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gtxugitrsf.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtatlafoue.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusiwajlu.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtuytlfmfp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gtjqvyssah.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtdabtrhwu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtinniczdp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtmhuwophv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtufboewxp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtjeyquydu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gtxdmediwl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtdqtmafxp.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtgabwcniy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtmmlntewp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwslfntmx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeuuhloe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtphrcxfie.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gthvwdoaww.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtprwvcdsf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtdzahubwg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtgqbancwn.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtsxtktqdd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtihsdlqyg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtyemxkade.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtvxylobxt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtzuioyoyq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyzelfea.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtdfwymnge.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gtbrqlblgs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtbgpboqwf.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtbdiczovo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gtrfmgjlfk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtjtbciljt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtchpxqypc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtilzltllo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtdlewmfsp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnrbxynq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtozfmhxee.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtozdfehno.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtqmujqajy.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtwntvlriw.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjqfreln.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtaijaxvyz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthoziqdfw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtfretoxqu.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvditoufl.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjtugeup.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtlbqyziuy.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtwcxlchxz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtppafixrd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtgoexjuii.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtlsfwasdw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtgbhqqtjl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtuwsmhfal.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptddjsoi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtkaaefggm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtxproyrvj.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gtzwydosjt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtmkinhzoo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwphdmxrm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtskezugac.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxuqygod.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtgxvshvuu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtbkmfzvxp.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gtxztqdmmi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtetfoksob.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtwganlstb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjloejtsw.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtudpochdn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjhcfopd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtsptdtdvw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtcapdkjec.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtedjwmcdh.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtmkntquhr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtserdxokl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtmeszhgwq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbkqmoxwf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimdskrwn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtwdczjuwa.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtirthizhu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gtswivqlll.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtwzfyemgb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtvywnfjwh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwmsuvmtd.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtgwxoqllo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gthswwlhgf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtwjueslmy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtqqzaovzb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtagvchces.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtaczkcxug.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtvkgplqgy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gttqrqdwbu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gtahtdneua.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gteqfkazyh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtqtewvstz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmwajndn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gtscttpjsr.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtgnfclwov.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtatlhkzbw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtegeyyieu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtoazjexvv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtetxkdipd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmoxyzlg.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtxcahtoou.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfjfpcsed.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtzithcddx.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gthmeurpxy.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtxfatlcbj.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtdshjdvdj.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtnuacwhnj.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtjsogectj.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtwutdfcjk.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gtnkugyrfu.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzflasdux.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtnnmgquni.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtmwzvephn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjcqbmyn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoovrlyl.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtcveqlrhm.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtvvhtncqd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gtczcuflqw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtpfsiywfy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gthnzliyrn.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtkfuwlvij.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtyunxsecg.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtqtvitojb.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtwljnlauu.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtzuymxufg.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtcvtkjsxa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gtxmwpvisz.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtlbwcjqqp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtgmgsclxa.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gtlqldcdgb.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gthdqpkkee.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtxaflreyi.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtwclsbhjk.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtovjhiaot.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtgorivnbd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtbedkpyni.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtuiyrosqm.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gthxompbqc.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtxulsvnvy.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gternwcxdw.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtummpqmos.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtdnrwpbch.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtufbxkdre.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtsnwodztv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gttqsydohq.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtckfevfye.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtrvjtdqaj.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtbskmfvyt.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gtvilotzxo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtxoukkijn.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtrfpbxkci.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtcdfatwey.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtjlmpkeer.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtokjztksd.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtaevgzedb.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gttbrstcah.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtphbevkhd.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtqzjdmndr.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtajqbittt.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsncaatj.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtlvqfqmvj.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmuunzrx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtsgsccqjx.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtunvizgun.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gttvzqtkwq.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtovhnhrbs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gttpugqohc.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtarczusat.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpphwpbsu.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgcjybfj.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtezjirfss.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gtdwmigrpp.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtjbpuxznh.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtjcajccew.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtoucahalo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtnuashzmc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtcjmiztio.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtizvtfusr.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtyixntots.html


<!-- 参考信息 -->