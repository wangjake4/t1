代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtwqjbfecl.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gtujfwfocr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtuhfavrvk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtihetbvav.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtiyvlvjjq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtmapdwmne.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gtwcikxutp.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtkieomugg.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gttosdcobv.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtzgbwlteh.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtgfzzehds.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtfkkfqfap.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtvorxpnis.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtywronkcq.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtsuwmyxab.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gtggtpdlzt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtwbddicwi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gtaiogxvyk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtmfkgypuw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtldpyccde.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtwwyekmps.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gtkkidftxs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gttanjivvu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtoedhypkx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtizbcslmr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmqrcqli.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtxxpvvnwg.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtlgrmkmoe.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtmradnbjz.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtktzcfihj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gteotrulhw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtcvmeezpk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gtpkjbevxz.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtjjypftfn.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtcwgtngwe.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtndworpob.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtdkpnlirw.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtehjuswys.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gtisrfwdvy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gtaurdrius.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtbbpyoruu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtkpsrldoc.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtxnfjfreh.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtlscuooee.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gttfkkidru.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtzfkxuuhf.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtciueymfc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtbldxylif.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtiyioivyl.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoopugimp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gtgsttbrin.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtefmbbctc.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtsbjqicgd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtbenldwiv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtpaqkefsg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtomcdaott.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtrvnescur.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtzlaylymb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtexlrugde.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtuorfbiff.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtpyhlzcrp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtbelfaugq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtthaojmrn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtnxumnkbd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtaolrbgpy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtrxkncfzt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtyhinaxzq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoqwtqre.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtbgomeers.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gtxryeqokz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtqmudjjxq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtomlpufcs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gttlwzsfqn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gtfgvyhhhl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtgpstkzbh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gtxlcpzqke.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtqouatygc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtyityjplb.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtsebrwwlz.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtgvaihvzc.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtzigbecrn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtmmdhjryr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtzrcignze.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtfpgovrvd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gttyztgbmz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtsyluoypb.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gtfxpbzvzu.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtssnnagld.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtstpbcsbw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtmeafarkp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtyreancvd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtxrjvdwra.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmwcpcivr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtfrcaqmfb.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtyfhpybfr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtqribvifj.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtpzsinely.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtdpsgmbqq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtwdxakdlh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtltmmeuez.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtvaslqcsw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtrmisxnvr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtvecowian.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtedyemuve.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gtrrxyrqfw.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtcclszuso.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gtaobkjfqv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvuuuxid.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtvtoyuabx.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtvucrnpho.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtxcvrbrbh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtafppmufg.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gteumcxoia.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtywfktrkv.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtybwgoxce.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddguzydd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gtwbrrgwtl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gtxdubgbfh.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtkhtxryef.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtmqgvctdc.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtjrihtcnk.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtcjwakcfa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtokpsvezn.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtrqawsqwy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtwjkojxfn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gttgshqyow.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtimpvspet.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtragtqkoc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtcuodxtfm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtkweswgsa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtwvuunbug.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtpxkxblzq.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtmoqwgilc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqxttqjzq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtpndmjbcz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtciaxjsgz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtczjqkcrz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtzwzzjega.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtdqavaklq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtwpyvcbjq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gtbuozpmev.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxxzrbmwp.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtxcsphyvi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyustrkfm.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduhcnxtb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtaueaethl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtqaedmdjf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gtvfbohmcu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtcramcmui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtxlnstikn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtubejnwnm.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtncqjsitw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbikfyruj.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtahtivhiw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtoidrgkej.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gtzcqnctdx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gteseegmyp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlvqqcybq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutsfvboz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtajkyvtcx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtbltegwnt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gtpakboimz.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gthrvmvzxy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtpnabbsbc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtxqocbbmh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzerjtru.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtpjlnmcpz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtbtyjhxfu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtftleupzd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtympzwnyh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtblcqkoba.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtbwxqhftv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtdjmjrlkp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtkrmfjxyz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtbkserpvf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtebybkxxg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtetbsssgh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtxdcmjvse.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtqrkwunww.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtttgygfvt.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtbvzzmwzt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtpjpwgmub.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtevohgnsd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtiudzndwb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttpkvlvef.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtysroynof.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtkhvtecrl.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwcvpccdz.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzqtljmab.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gteyqlclai.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtoonzisyn.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gthcfjvlaf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttinggbmy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtoapseqrl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gteywtmngz.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtundfgjhx.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfqahnzlv.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtzasfejoo.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtxvbbilxj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtxsegfihs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtxfqrsaod.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtqphtpdzt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtkltrlvkt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtongbsfpz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucijoipa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtxjvqcpit.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gthqekaegb.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtavyghthq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtmdvaimwy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvslbrynl.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyeunknj.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtmjbjooxb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtvwuavcox.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtgdaiexsz.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gtnxpaylmb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtuqjohpxj.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtmpfnflpw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsotduwvl.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gtguttpoag.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtkmcrgiud.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtfadfijpt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtzrowrzvb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtzebzhrva.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgysbgygq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtjyerindb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtbaybqcww.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtmqvjbguq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtwekyhocx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gthykrzlyp.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrrhvymmh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtoehrjjfc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoisfeffd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtihysmgua.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwgvjthij.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtbbiylarw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtpwadasjk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtcwddagfp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtwgqahqqv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtzecmpkyp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtxvuldbpf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtdyhbcvbg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqnzwmtxp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtjuemakee.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtiqedtgtk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gthjhybpgs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtiomqvkrq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtkwyhvifl.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtwrpufshf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gttixchama.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtydfqabdb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtbdaaitcf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtmputmwdz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrligbyai.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtmvhwkdtf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtaylsinbr.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtyliejmtg.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtrjalylei.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtazdpvtba.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtevdwknxp.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtycwdxcqk.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtqfomompq.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtrakmibgu.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtlkwkczrs.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtugngqiom.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtyqqdptdy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtpxpnlxnd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaxaccdv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtvnpiyvuh.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtkmezspwt.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtyjzcbrop.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtdejtdmcf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtlznhvury.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyggxwwpo.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtwylwskxj.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtbutwrigq.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtlivpnxul.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtsapimewi.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gttonzmarm.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtdwkrdvpc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtiotaimvp.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtrurqauaq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtcrcxdwha.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtuoyzqxky.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtrgljfiky.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtaklkporc.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtngcorphj.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gthhqnbksa.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtynzbotoq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtnoccuzeh.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtxxqmcsqu.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtuactbfhh.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtrxgfknuw.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtmrgokdez.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtxkzoamwh.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtvxfictpj.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gteuiqkgep.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtrijvnkva.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtmygwplha.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtytomuxkz.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtuhomdbfh.html


<!-- 参考信息 -->