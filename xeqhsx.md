代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gt2qwecjwos.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2pqtgajkt.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2npyzclwt.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gt2viccvvwu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gt2utrdlshv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2kfmhwrjw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2vwokpewt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilgyutob.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2tlpamhfe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gt2ifbpqrip.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gt2wnrwymka.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2gzddwvii.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gt2aerlmjnn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2krqsbnxm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlcnzkar.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nviqpdrb.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2rjelzxhx.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2fjdxjisj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehcuslvu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzrpsusx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2jvbkmecu.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2uunausbo.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2usatonnd.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2oslmngbz.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2fxlxxyth.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnvbabkg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2dwmczbat.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2wutwafve.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2brxniegy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2qsmbzzyp.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2jovcgvek.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2syrmzvbb.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gt2mxkslgig.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2lrjqoojc.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2ehdrylud.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2eiuoigxy.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvrfrlyy.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2mbiweeuy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gt2pfmhmcee.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdtywfhx.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gt2xzvduabe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hczvbxfv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2gkjthowx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2ufbfmdey.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rqelykoq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gt2eieoxlii.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gt2iupanbga.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gt2wesiocgj.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gt2cldvhmnm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gt2qztnhmcf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2pghlpjbp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gt2kayotbdj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2aayamxts.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2jjbakbwj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gt2xsrumuut.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gt2azcnnfmp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2twlumdnz.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gt2bbkadvwo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gt2jvccdrkg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gt2vofsjslv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gt2tkuqthzu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gt2vzcxevuo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gt2euqvtovy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gt2kritsdij.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2idqxdiap.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoofapod.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2cpzalyul.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gt2qxbyibgj.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gt2fjjpjohi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2pcwjawtf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2pshmzjeg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gt2dumihbcr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gt2dagcyobo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2tntfvkar.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2ilimhxqy.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gt2hrcejpnt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2evbepgez.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gt2gigqugvv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2befxnxgx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qdpdehtv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kykpwmpx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbgzpfdi.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2nybtnzin.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gt2sznekhso.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkdpgwoa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gt2plysnsej.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gt2vbbcmofd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yygvfuev.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2wyqdarfw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnbciqep.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2hvdbrrxn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gt2wyonzadk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tanke756.top/Article/details/gt2keauwprg.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gt2ovnmthyw.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbohnezv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2rqxtgakx.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2leyfwupn.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2bajjhici.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gt2ppwgoquq.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2qdwsbvdk.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gt2ofgiziwh.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gt2xhbfzslj.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gt2wkikvvmp.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gt2fopiyplz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gt2hpbtmyom.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gt2eutwugpy.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gt2xdakvwei.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzpiucjj.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2yteiqoko.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewftloji.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkygsmtq.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvfnnmgq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gt2pvmdsfxx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngfczkpt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2ahrpaens.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2nyygjzac.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuxlrrtw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2myydizpb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2cbyoshbf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2ucdiqbrp.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gt2ohanpvbf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gt2lapawuyr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2hpsvqirb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2naujnyxb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2ntcktovq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2rxlmfgur.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gt2aqfshvui.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2cvftaxwy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gt2gfncptke.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nfceqrnp.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gt2oazztxyp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvqmpytq.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gt2ehwhcxvf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gt2fwoyvinn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2hmgfyycp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gt2seiixprv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2agvdmdvo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2gzrtcpsr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gt2wngtpssh.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2wmwfrazk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2gkmxhphf.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gt2eukjppzk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2rxnijjnk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gt2ucigablv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gt2cxieacdb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2vudusrqm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2ipsvqxsj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lislyxco.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwwdnkgt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kthkjpwo.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gt2lgdbnpdi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gt2iyfdhkqs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2dddegvwt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2wawoczqt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2iekwpvsq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2cblkpnpk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gt2pvqmesss.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gt2khphcayj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2qyrgrpfb.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gt2qhjcszmr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2noauwbva.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gt2dnvxnppi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2fxycrgpb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2uxfnjwxl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gt2sfaozofz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2araqzkno.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2zphzusox.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kaozoqwj.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gt2fuhasmno.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gt2jowfnxju.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnkkyqsu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2aevrsynr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idfbqrzb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2fipoofns.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rydsxsud.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqacoxhy.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2dbtydjvj.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gt2grfqfvxk.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2hcokwcro.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylkmxrti.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2xnwrwlnm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2jgulfelk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2tbdxyltl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2igjwuskt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ygyvvlai.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aemvfleg.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdwmnpqt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2osawfvza.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2egvctqen.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrqkkajf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2mdmvldix.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gt2kkiesklq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2mjezlqav.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2wasakdwu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gt2gbohqmgr.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gt2esqbjquy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gt2obynjcvx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnvdifct.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2ohtqnkyn.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2vdmqekfu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2badjanpp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gt2jvztggqv.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2msbtxjox.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gt2ludldxef.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2ezfqmcoh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2gxowmcqk.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2jhwmrxap.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2wiirpsii.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2zzgylueg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2pabinjwz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gt2qchmwdve.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ekpbctoi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gt2qkkhbnkp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfaoxhdp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2uguylbbu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2ohyburtw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2saqgxmnz.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acgwzmcm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gt2xozzqkcr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ulxwbqfu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2oavjtsxt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpudfiub.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gt2vzfewxwa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2vdjnovmz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2aoykmyhe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2lkfzcpvh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2yuxcsocr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2kemvmxth.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gt2egvegoco.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2guyzrejy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gt2oydhltpt.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2sxzxttrr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gt2mxlnheyt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gt2ysyukmvc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gt2ffueqzxm.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2yxbtoavv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gt2nknfxczb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjgwrplq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2soaaovuv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gt2mgornxiy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mztuoola.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2psmyxxun.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2vnskegiu.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gt2dfmonylq.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2fshrooot.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gt2qnxffjbq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amxyfpbn.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gt2bothutwq.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2sefkybtd.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gt2sueejuyi.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gt2hotnfzic.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2oaugshll.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2oytsazqa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2pmkvelnw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2bfgavvma.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2gdjbmgeg.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gt2vpyfmibn.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2cijuirdn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gt2uugfhsiv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gt2krxwtqhb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2csgoajsc.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2rfcyznli.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2qdnbwhoo.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2qgaeexhm.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2labqpckb.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2despyera.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzwqiaor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gt2ubdsmbyy.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2xjcubkfp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2tgkwikrm.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gt2gnzlatep.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2egyvqmag.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2vksmnvvz.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofwwyxfm.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2dwudpctw.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2rsyesfni.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2odjpnobq.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2njlqimyk.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2ohzpdzpe.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gt2odaluawg.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gt2pofyiavm.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2qlgdpaxz.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2eklmsdiq.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2frjfaruo.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2xilxjtyq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwptdflx.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2ssumshoz.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gt2qqzdlcpq.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gt2yygdqsob.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gt2dgmyvufk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cysordto.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiafzzdg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2caatkoka.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2vyvusgjt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2egtojaxd.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2sxmtatvy.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2ofsklzin.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2octnexix.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gt2vdkaamxd.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gt2ykuhivvq.html


<!-- 参考信息 -->