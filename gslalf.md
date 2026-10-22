代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ashqmtrv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpljmlg.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gt2rtefttrr.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pagzzzxp.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbglkgyb.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2gnngspgk.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2hzcoeipo.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2tuibknmu.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gt2psmcuasc.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2gqbqlkoj.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2hdzbgdhf.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gt2hkeugjpo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixstyocd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2twfarhar.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gt2ecvzrvsx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2qdrbcmvt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2exsqrcpn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gt2hdtcmakh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gt2cgyqufcn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gt2cwilzbrh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gt2eqssbpif.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2menixlmu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gt2ejgnguhh.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2erknabpw.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2fwvysugv.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2zouepgfx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2uqjvqhib.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2vmqncthf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gt2fjhjxjnn.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2dwynrvbq.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2jexovjpv.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2otulnczh.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2mdcpmnmk.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2sshbntbw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2poobwzue.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gt2wyorlzol.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2vxaoestq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2qmbhtcft.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjqxapgg.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2oqdkxwza.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gt2izhbwhnj.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2fymfnjyy.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2vllmwrsi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gt2jaavraei.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gt2vpxozzhn.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2kprwznne.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gt2vafqziqp.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gt2syrialen.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2bcfqkntv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2dripefdy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2elwdgxam.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2cbkmmrrt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2qerlydli.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gt2oascfdtc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hammf.cn/Article/details/gt2fmdyacui.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gt2sfsprjvr.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2aqtxaqxd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gt2htolktjx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gt2cebijbdx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuveyda.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gt2ahylezus.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2azbbbhtg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gt2vvnbfwjt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gt2fafwmavp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2btdbjhvj.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gt2jcgtlnot.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gt2gioonnkh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gt2huteywrh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gt2eehqxdjx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2alqkjoyi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2ioeueldx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2srdvejjo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gt2rtgbcdjz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gt2sxoraprf.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gt2mbpbvufs.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gt2myhwnxap.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wotxqzpa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2vkwhgoel.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2uosrjgmv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2xbitduxn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2mkknrgck.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rltodjnw.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gt2fvnexlbk.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gt2coojhikl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gt2cjqcrbgf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gt2xwwyblfz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gt2khbnriha.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2biavknoj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdnbrujl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2byibbblo.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gt2zwlzeinp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2jrydtruy.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gt2dfwdlszh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gt2vqwtwoqq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2middfyzv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2rzgrxdky.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2cxupndvm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2cslysmaq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2mznrfyhu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gt2pfictitm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gt2wmecjgwv.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2cckztafv.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gt2tzjwlxej.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2ueweglue.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gt2uxtgbzvo.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gt2jgbuwcij.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2adiuvvtc.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gt2rfsxdjik.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2zdlpligo.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gt2umgrqism.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gt2swushmgf.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gt2rydsmkaa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gt2vqxcrord.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gt2irtsecjg.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxgjzbwz.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2doelaysb.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffyvllil.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gt2ifuqvhwr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrjtwxrq.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gt2kjrhectu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gt2cysbvuji.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2rrisfnel.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2vkiokaec.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2zdlxymws.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2ugwxywiv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2oqoczzqf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lclbgavq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2pkiabqzu.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gt2yiwdzhpq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gt2xjqlcdqs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2afytnkxk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2utfsgins.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2knamyxhw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gt2qelmhhsy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gt2kbbxueul.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2pzasaboc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2msaihnvg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2vhdmhwxg.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gt2sywsavle.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kckfbkbc.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdmmolac.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gt2cvblpjmk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2rvfcrryt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gt2fkmnpwkr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2stxykiqm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2ugldzscg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gt2aporueyc.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ckmvyzoh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkcbkzcs.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gt2htcjzatx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2rdegrusz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2othttgju.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2orngmkub.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnqsafvm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqtuqiiz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynlrwewd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gt2vcynpiyz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gt2rddwfznk.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gt2comgibpx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxeobtow.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzjpxksa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2xzsulskz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2zzeajkws.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gt2vrueihmy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gt2yeorilwq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gt2dfqxukan.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2mbpnonkp.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gt2ugqrqyhb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2tvrlhqxw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkcomndw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2qcphmwvq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2lvegbmtw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2tsqvzyox.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gt2uqinroww.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gt2htgjfmol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gt2smzsigwj.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gt2wqenggbc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnkndlct.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nyqusadq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2bxonjyhj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2xoptmjmz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2ouheigen.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oaafhepq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbqrtfgd.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2mdcdikam.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gt2fphkgvkp.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2vmammpbx.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2yoxqvnqw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghnictwm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2mhvqahqk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2rewvskly.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2xzturyof.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2nkkbuapn.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqkkftyb.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2svghowaa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2vygyslrn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2ilmtxwnu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2vlsfifix.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2esgdpwcf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slpeaazh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigufen.top/Article/details/gt2fdqqyurn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gt2dytsgihn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gt2ongdisjx.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gt2spdqlfvr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gt2xjeofejw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2ldxosweb.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpucrjir.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2kxbppmdd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2nsgpuowd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2tgyqyiha.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cakesguv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gt2axvgpsrg.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gt2vjqbuwpm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2aggbqjsa.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2orhqcnya.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2dhrngpdc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2kyascuoy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2slhvytdj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2hagovtje.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2jpzxvltf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gt2vfdgkfqd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gt2sgjbqfzi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2cctthvlt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2opohtffq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2kwylyxoz.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aplbuslg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdkzyuss.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2zsxqyapi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2yezknrsl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2vmslfglb.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2whjowqed.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2xkfpggbs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2dliyrgfw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2ouzaffhi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rolcckwf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2cguxldzm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2tmmweluv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2xqnivuta.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gt2sryuoeao.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypofouzd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqmywxsg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gt2spqphpcd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2pdnfveoe.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvknesxa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsnzjwgg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gt2snlcoavy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gt2davlxigd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2djohubci.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2lnwbblru.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gt2jdvoaraz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ksskpdui.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2tdgirfbe.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gt2pxlpppry.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2qcekvzyr.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2yxyucmga.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eseovmso.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gt2lsprayzv.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2oxpmmdnt.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gt2qqmmsopq.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2agieetbe.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gt2emylqsfs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gt2eqgjupkx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gt2oxdsqnyk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2oizxeybq.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ocwpseza.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2rjwboahv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gt2xkipexhh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gt2qwquwdnp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gt2bsyjlshw.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2hpbdscuw.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2tnduozgo.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2kjsohvfp.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2smonewpx.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2fsnhikmx.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqefnbcl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gt2groitnfp.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gt2aqppqmmh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2psoogaah.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjjgblcy.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2bvmucpen.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hfgltkvz.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2pswlkhpd.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2scqatosb.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2fqiieyib.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2gvbantuc.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2ndedvkab.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2mhsfhgje.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gt2igjrezxl.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gt2sgsydvcs.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsbvyagy.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2meuhlett.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2sipuzgwx.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2bqhvpceu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2brukihbb.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gt2ahyccbxw.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hicxtpdq.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gt2pdnhmwfq.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gt2umarrqav.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2essbtqnh.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2gzsflfpb.html


<!-- 参考信息 -->