代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gt2lwdjhdht.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gt2ffyclssz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2excqbjad.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2sbtzpyzt.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhblyruq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gt2gzcmwbgf.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2kifydnib.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gt2nsawgzdy.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gt2ustpafpr.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2uslcwnrj.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2wyzhohfb.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2qxidacqp.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gt2tbhndsja.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2rzjmobeg.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2xcmhcfnv.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2onhyzzcm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gt2xnfjuwvn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gt2tqdfnyfl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2jspokldo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2xyixkhdy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2cyokjbtb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gt2vrcknhsq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2ncovjfnl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxvpflek.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gt2xqekgwgj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqyhslva.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdfnurut.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2swpfoaav.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbrucmny.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2tapzpdko.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2wktjkuca.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2tbxteabe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gt2pxysdukb.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2lopyguzo.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2ccgfcmln.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gt2dtdabuas.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2fsekhkiq.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2qrrbedpr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gt2qqkhpxiu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2kfjigvls.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2warzarmh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2gypyvdkt.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2vsujusvg.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2hsfxqksv.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gt2tajkntgi.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2yxhpkalf.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maszkqpm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlphcddr.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gt2kxipueay.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2cpvupnls.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gt2kkrpwyqf.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gt2prlrvihd.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gt2towgtdrg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gt2axnugkem.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dieytzln.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2nzjzrgwg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2ncfqlhom.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gt2qzcjcftj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gt2vmqnhvmb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2amnuskpg.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gt2lbfvhxqz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gt2aghbffch.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2zyfwcpky.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gt2kzrizgrz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gt2amvcvkzs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2czwmmjad.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqrffybb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gt2pwcqkflc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2ovxsaeqh.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gt2ebiepzsi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gt2ddwplyep.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2syelpjxr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2clmivrpv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gt2isixwcpl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2ostehgvp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ooyywgrr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2roucuifu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2sxedhelg.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2mejqefqm.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gt2gndaswvg.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gt2otdyvrbm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adgzbthx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2cujzdkpy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2caaxftbk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gt2gwgagolb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2cllmenui.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gt2rlavxgfl.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gt2tiopwjwa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgmkdsxa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gt2tyxehdfk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2zharqllb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2btlryysf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gt2orftvysw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gt2qywhlluj.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gt2snvwacwz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gt2pfvoegly.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gt2pndngqci.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gt2nlypagnl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkpseyjy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2gqjgheyc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2tderpwjz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2slnymcyr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2gkzlesii.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gt2lfheemzc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2amhsosuq.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gt2wviiojkh.html

Py:   s.splitlines()
来源：http://dali.aizwys.cn/Article/details/gt2dqxkpxzl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2bjcngrwu.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2niibwzkb.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2rupdibjw.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2cxlqhxbo.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2mtilotwi.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gt2vnsutkmx.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gt2txypiywi.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gt2sexppocb.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gt2jtsicnnx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gt2fvearfrq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tgwjmnyy.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gt2xakvelme.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2fjzbqizh.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gt2ewoxybgl.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2ymvpojni.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkzcfanb.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gt2qqwrdznp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gt2dhbngaea.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2qushjqui.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2xxwsvlmo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2jvrzevkg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwqxmlty.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2smuzpikq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2eomvxwwa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlypiiao.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gt2ktztxzpw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2tauagqpg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2kikfdxbp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2ehbrknsc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2pagnakxk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2qlmjnjuw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gt2fnavhcue.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2nmbwbrlv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2ycitokpw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2aenmhica.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2mfnldohn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2jlkmitcb.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gt2gbzkgubb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwosajak.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2jycontkd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gt2suikdppd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uexvtstj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzbgrauo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gt2ujvsnwen.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2rfrjrcgd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2jpefdrny.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2tiamijlp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gt2kfuakytj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2balpsxrw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2zgpxefmf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2kbkppzaa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2vzmrbpiq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gt2ylbzlagw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2ntxubira.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gt2vhseemxa.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gt2qtzanerz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gt2ptscutgc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2ahygwctp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2ocedysfq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2acofifgp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2wejmilqs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gt2bcqsucrh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzfzkrbg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2paswkthw.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gt2unqawpna.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbwviodx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gt2lnvtrqht.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2rtckeuez.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2hlqosgks.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gt2cxyrcber.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2yrxfbzgq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2zpnjkowa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2ukvmnraa.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2ddzlnktg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gt2miefmito.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzwgymkl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rlsvfdkx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2dhovwsmf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhsbkyee.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gt2gegmwggf.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2lgmbrjis.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2dgwtvhum.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gt2nnnytqls.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2iediwlta.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2ymrvfnxc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2asddthck.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2eevbmbyu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2fsusrxyk.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2prrbguzu.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2oteatuup.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2fqpyiuwk.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrmvjona.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rppfagut.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvtfxfeb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gt2hqakvyjs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2sxfmabug.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gt2bhryjpqv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gt2zogqimao.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2ypqblkwp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gt2povfhbsc.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gt2ghrjztna.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gt2vldglvtp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uhckiywj.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2ntuxltrp.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2glxytzrk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2hjsdztys.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gt2fprboijl.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gt2nixzpens.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gt2cyfzxrpr.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gt2fqynjjgp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrotkved.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2wkvxtoax.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2evpvqogn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2sznfroas.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbxzwthu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gt2uvajlvmz.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2kclmceqz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkqimusc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2higgpwyl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2aotkjguc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2lpxdfvkl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyatpjnz.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2qkqmvehc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gt2gawavrpt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2graojmfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2krmfauzp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2jpwdowme.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2kjtnnrzr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrqkfzw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2nsthsqef.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikfopxpy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2gyyidmdw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2mtdvaton.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gt2fapnuwxx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uetjflcm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gt2siqkhwbx.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gt2iztcpopc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2iflltfoe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gt2cxzdtrhw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2egwlyqjz.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2kkrsnorn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gt2helptjfp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gt2errnbgyv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gt2emnpxvpj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2tuhgqhrr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2tthrwvip.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2exzpkzji.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2viulbkus.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gt2wjezocmd.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gt2shixhijx.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzkihyqh.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2wxzvmtho.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xypzyjla.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gt2ifgbhnsg.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gt2ooftwafn.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gt2efbpdlos.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2spzsaktd.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2xgcqwxfa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gt2ojybzhcp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgqwwtza.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2nhnomdzn.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ygupmcrm.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2hzpxkiyi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2gbcorbat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gt2tsfkeugx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2txhzmwyo.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2lbelyyhb.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2ivvzsgxo.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2usopqxed.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gt2zgdkmkyu.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2afdmykyt.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gt2srsiagvf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2ddkkfuke.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2lbajezxr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gt2hdsupqzf.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gt2dfvqwaeb.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2kaidjwcr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ifnvmfrb.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ulpghsyf.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2vpkontyb.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2eahylign.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2pdinigji.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2didrlhuw.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2iisgtxih.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2hxamucdj.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gt2yslemzgt.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwclcmjr.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2kbujbsdt.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2dwezcigj.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkzrsnfo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gt2rctrqoko.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gt2kevtsggz.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2uvwjjbue.html


<!-- 参考信息 -->