代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gt2vpwweadi.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2gvfqfkox.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjzoeuax.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2ytevpopn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gt2tybshwzo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gt2zwtisonh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2uhrrdyld.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2znbzlboz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2vrmpqwty.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gt2aspnnris.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvsbslpe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2waluwplj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gt2hjjsogpv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2oyuccovn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gt2mxvztpsq.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kswrfvpa.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2chjcfryy.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2piltmyhj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2bzryigod.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2axnynirz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gt2tlcybycu.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gt2nzxfelzr.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vscbwljq.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2rsapslrn.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2efwapsum.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2tfbtpiig.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewwmuyqj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2gihovcgk.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2dmmvsxpk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2objkixff.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gt2trzlznvv.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2ojzeirkj.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufwgwpxv.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2yqadffnh.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2sonjbpmy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gt2qqbmqkil.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gt2hyvtqpqe.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2dwhyxgba.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2edqhldqf.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gt2lvfocldl.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gt2qdzntrwc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gt2qpulxztr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aamcjdxi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2esceqapk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2hyvjzyws.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2wogpykkk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gt2vttqmdby.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2pplbcmmw.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gt2uvceuouo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gt2sjvoegkr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gt2bqwzyfub.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2vxuiugca.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gt2tbcsmgrx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2lwybbiir.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fogebcal.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2qyrwmpba.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2ualotrkx.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifvdtfzq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gt2bxcczifi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2svyiucrm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qarzqooo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gt2ybrixbfu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2qdopehkm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2rtadpkhh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2yvyhxgyc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2owxpoivk.html

[E16] 数字千分位
来源：http://dali.guannengcc.top/Article/details/gt2nggqehmj.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gt2fxvqpafu.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gt2uyutuqhr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2wbaeivlp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2rqmzgiqu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gt2bevbwvyx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gt2auuissxm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gt2bowbudhl.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gt2qyzwrkwl.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gt2crirhdtr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gt2cecedyvh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gt2zhdvkqum.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzrrgkye.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrwdyeus.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkrkzsbi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2snxggwph.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2avszntgz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2ftdcweyg.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gt2gupzbiru.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2sfwthbvk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gt2ssnxbjly.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gokczqqp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2xmuizsar.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2mnhulfyi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2xumldejh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2svdveqkj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gt2uhcjpvhz.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2rfyeutgo.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gt2piumbbvo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwmiqorg.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2ziuzpoww.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2jihxbchn.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgnjfzad.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gt2yvwnadsm.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gt2onxjpgik.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gt2umokozhp.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gt2mgrccqnk.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gt2eekehyty.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2askqkjws.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2npwbubdy.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gt2wrwsizum.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gt2oifpooju.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rnubsdec.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gt2ckgyyxff.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2llnmgocf.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gt2exbjuwru.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gt2xaymnsuf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2symwnkes.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2jswrgoze.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjqjuukp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2vkrkmloz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpnxuecs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2fulfdbmo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2ujmtoazx.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gt2ycckqkmd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2pldtjagv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2bqnpwoxn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2jrddeqkp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2oyhwjhvf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gt2xzhjiryv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gt2ylspmije.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2oxktopan.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gt2pihyazgs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2irkemkzu.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gt2kdvkmnvu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2fdkfzakf.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gt2yufrepbt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gt2hmngrkka.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2hzseywjc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gt2cucgfoxl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2cimhxbzi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2zcmtfkjc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gt2qljtmvuu.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2fllfirpp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwxtqrdq.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2wrxsmxto.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gt2sbpuydti.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkusfuej.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2xjatvxqk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2jrrdrtye.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2iayhgfyt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gt2fsmvmdys.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfidgjlx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2vkjowngb.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gt2afjlxgqf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gt2hfuduyjm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2lsuygdin.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2uykukqdc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2fkbhsgoi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2cypxesru.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gt2hxlnvsby.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysasrplu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2srxgzwaw.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2fexucvsp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2chxnxznc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysenqmeu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vaoiahyn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2hkcenfqx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gt2dtreslvj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2dbdubkuh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gt2ugyhizhu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gt2ehfllgon.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2igqpmeab.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gt2gzmmhfwq.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2aysvqrga.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ltzgdpsi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ublyqzke.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2plxsryeh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gt2lneqywdk.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2xmsccter.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2owivmhlq.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gt2inmjclws.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2xrwfctsd.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2cmqznfso.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2hlnbsgkn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jexfsalr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2skpkugmf.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2knxvbaas.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gzbtbfrd.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2wloukoxr.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2eihyubib.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2tbwjuzaa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gt2znbsysyd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2qappzlwq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2wusodyfy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyjfcxth.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzeoxwfe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxjjohtz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gt2oipvcnse.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2zajrvmhk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xutdortp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gt2weollfpr.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2tywbijjh.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2azdldjlb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2todaiifc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2ayfszdwr.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2xulqzprj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gt2misaiffm.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gt2clxtgtmp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2jjlgnzbe.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2wfdzfpyh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2dnuracmx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2wygvgkrs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2qhifgqbh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gt2qhnsbtwi.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2pzhaknbs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccnjilwm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gt2uhdkdkhd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2fambpets.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2gmsfjgba.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2vcbzlviv.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2vstokftt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2vvqdpbmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2cqlpbaim.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qbqpnsde.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2eshwvdkw.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcwwaznp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2gmpbtcuo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2kzwinccv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pefpurfy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2uunfrdyc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwgevmpa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2vfukzlso.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2pxzrrclr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gt2uvgfbqay.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gt2mifwdfaz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gt2xuaczfps.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gt2cnuqqxqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gt2hsllfbcl.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gt2pomalaew.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gt2nbsywhaw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gt2qplpmivp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gt2bworixqn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gt2dlttvqku.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2josndlom.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gt2nygnvdsk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2efqhezzc.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gt2ctmtmqwk.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gt2eqjpdarr.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gt2ezhkhfvz.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2xjikzdyi.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ekeijimr.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gt2rmdrxiif.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2pddalmrr.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdstuelp.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2omuzylcj.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2vmmidypy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2mynintqi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gt2pwwdurug.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2mlaztsho.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qrkpojfs.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2ozsunqpw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gt2kdpptkix.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gt2aevbnerx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2tjzkoyuu.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gt2dmijnpfz.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2dzgimggs.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2ofmfifbm.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2cegqglcu.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2vbsisokc.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2ohpljevw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gt2jmjrivfh.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2upzqzjik.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2miykidua.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tovxwnic.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2btnxhgze.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2elkbsrns.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2cfxeqlqp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nuywjrok.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2taocjwgr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2rcxdlkss.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2dcttffgi.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2uafmnspd.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gt2mcmlvzpf.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gt2yrqfiyaa.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2uycwymwb.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2anqwjzhv.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2bsgaqyid.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2fnlkvvtg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gt2qeucxtwt.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdrxzdop.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2mbqjgxww.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gt2pqfuirjk.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gt2yvuvimsy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2rhimldmz.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2efbodspc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2yldwqkvo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2olsotczs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gt2xezmrixw.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gt2wxbkbvsn.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gt2hczsxjkt.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gt2seygiige.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2fgavznme.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gt2gvvsflbs.html


<!-- 参考信息 -->