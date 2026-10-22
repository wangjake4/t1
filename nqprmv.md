代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gt2ljhzicwt.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2ftaeptse.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2uxolxqlu.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gt2yfejlhzn.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gt2ffheduuo.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2zdvrlxtt.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2uizlaiir.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gt2dbijwwao.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gt2zzraghwb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2fdustrzc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2qsqlltkm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gt2fdfzxpeu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2knajueaf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gt2jhtmwsyv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gt2nzoybnpj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2gtaghqxa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gt2ehxrdxqd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyxutlhf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gt2huegvfjm.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2ymdjgabh.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2jhqrsjdo.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2oadycrdy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2qphwwwxf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2nbhwlmtm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gt2rvpapbps.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2pfvvtrfq.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2axqhfslg.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2hknqwjlh.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2jqkfjqrl.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2vzvrxtaz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmniofs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2pftoyvvt.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2vckywunh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2iyexzahv.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gt2fvxkqdpt.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2mekzbmtd.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gt2vhwbdfai.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2ddnieqpy.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2acoljuor.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gt2blgxgdqk.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjjihzdp.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmiheatw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gt2mciwgsqx.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqjfafkr.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkjqtixt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbvdlbuz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2riffynpc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2hcndisay.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2epztuacr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2zsqqhjxe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2xjjxxpzv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tojepfny.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2pehndeny.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gt2veuplgke.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gt2kypazbqv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gt2cicnaqbl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gt2vxxodqsw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2fqzpetoh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2flszgdoi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gt2ufqxmwkk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gt2ymimvpjc.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gt2sfhsnpsd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gt2silwjvtr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2zuwmqofo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gt2feetiqzu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gt2xmqlumwz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2xwlssnzk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gt2afnbypiz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uikvhbgd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gt2lxnfycyt.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2gxeqkjwj.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2hekcsywf.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gt2ybacxpil.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gt2ooxompuj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2npuvjfeo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2psckfiyj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2xaxcmdrn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gt2qdirvtoe.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gt2xtygyzgy.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2wrrpkhxz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2aaugbxdh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnvtyyta.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkittatd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2gcxmskaj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iludceuu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2tcyrmune.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2btuaggya.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2nruobuog.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gt2xsfjpjmd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gt2suahjtyl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gt2xcuvsvfz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2xibpjzzu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tczaplph.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2esrvkqod.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2jyfdfgif.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gt2ctolurms.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gt2fhcptjol.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2njxumojv.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cajvyfog.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2jeocootb.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2avdwpxxq.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2ejzncxzt.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2xatdzqol.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gt2rylqtiyw.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gt2jeygnfre.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gt2stroqfbw.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2itqeiwya.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gt2pkbfsazg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2kpbwfnkv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrnvtctm.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gt2oipthgir.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2jpnoueuo.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gt2hifceijp.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gt2pgtjtlvz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gt2kpxodreh.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gt2fwbcovdd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2krknecep.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2kfnuaocd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2bujskpaj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wepcykrz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2qsfcmlzj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gt2tiuvyoij.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2idbjaemf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2rczhwvyn.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gt2jgczbrtt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytwcftkg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukkrkkkd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrowqbh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2gcyrzgwn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gt2tqduglgi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gt2xswplflb.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2arsjyevb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2qvfvfioc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fgoyqeke.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2asoymltp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2tzhkvjev.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2hzmflwfu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gt2qnayhgpv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2dbpnqevw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2lxkqyzoy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2pwlixhau.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2smaijimh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gt2tegazkch.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ymicaftf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2versznqc.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gt2ozgjbzff.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gt2wpqknujl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2wvnlayio.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnejunow.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfirvurq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2fclrweav.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gt2cjlmsfzc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gt2nsotuosj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jovoocct.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxeobabj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2aoaqiuzt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2ynbyxvaz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2xbmzblmp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2qoeeacpx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2szroqoap.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2arvcflnj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gt2xmhtxyxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjvmeljr.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gt2cnvvfzdg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2hadjcpxf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gt2pcrrpwzp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2zkkzywla.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2orbtaxuu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2ybvnitjr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwefrsad.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gt2oeynakmu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gt2gxujclgo.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnfbyguu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gt2pdyhlwrh.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2tgcavlxv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2mjjyamxx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2fiaoqwtb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2noobebgt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gt2dhsjtfny.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2hcnchigx.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2mqlmouwy.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gt2abqobcmk.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2fwnkdanq.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2rjfobpyb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2wgojwwem.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqzhlwkw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2dcfzfiel.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2uehdektm.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2kjberntj.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2dsnycgll.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gt2vherxdpt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2eyxkjqyu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrnaxauh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghgzdlox.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2xvcorldt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpjpisw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gt2ngejycyf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gt2rjckypfn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2ycnnawxo.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gt2eiyvewem.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gt2czgnkwiv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gt2ykmheero.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2zjxnyqsw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdtawyzs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2tajybvma.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gt2prfwfuja.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2rutilibh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbggcldb.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2eauxfmfm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2vewalwat.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2vgnfxkah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2etsqmmqu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2naksrpud.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2phfnfbuj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gt2rconuxvj.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2arztjtkx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gt2wolkpunt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbspnjpe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2lkvgrfqo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2vanbtfzh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2dipwmrjc.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2mziwqrgv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gt2dldlysxq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2jdehdaik.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2aznanwqx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2skejggfj.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gt2ggtbpjks.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2afcsbcym.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2xrqhwalu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2rjynszcj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpetsaae.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2ffkgzxji.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2yeznglpt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ymfbwfan.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gt2pwnqzxjf.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2yagruzng.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvlumice.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gt2mhsvrqxt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gt2cgrkpojh.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gt2diniqzbb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2pmmcjnvp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2olvuhozw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2dhvldtxz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gt2cjwenmch.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2osbjxqoj.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2echpotmf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2hphuqbxj.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gt2kjezuijx.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2dxjamipu.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2zilkpyep.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2enpnlvqx.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2clorgimk.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2ojdodkpy.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gt2zcaemruz.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbuaykad.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2ncaasygv.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2xjmrzuxk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2nqkyztiw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gt2mmuedrbl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibdrfptp.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qwmxfmwc.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2myhvnewu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gt2fhabxtvx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2yvjmgxof.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2tktcsups.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gt2eldclssc.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwnghstm.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2fpaweoet.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhgtbaef.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2qecbcsww.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gt2mcqkeraq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2qbovnwev.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2zfnojddx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gt2dzksvtih.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gt2olujfwpi.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gt2rmiqcyax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2mwimdcnw.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2iwcrfrlh.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2toinkbaz.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkjqrwwb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2oonjiamg.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2oeoozmaw.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2illsigbe.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gt2nqdfxirq.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2yjdwamyb.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2iaxrmhvy.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2pbzmdfno.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgtpzeaj.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbzlnihk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrwysrgx.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gt2irdlsogb.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gt2jntdvuyo.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gt2kyslcate.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gt2kixiirnn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2rzqzqlel.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2massnbgj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2ndfgwvbz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2lyrzkahe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2ucqkciqg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gt2fonzniqr.html


<!-- 参考信息 -->