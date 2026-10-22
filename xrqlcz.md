代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2vosxdyqm.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gt2mahgjneh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2sifizciq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gt2pwnnkocg.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gt2rauywgkn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gt2ejshctbe.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gt2llctdqfg.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovyeamzv.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gt2ojccbnsp.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2xuhsggah.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2wyarqzcr.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2utcyrmqt.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gt2owqqfaaj.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2flsefxbs.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2uzlhymna.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqokunik.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gt2xoclcaqh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gt2kgxxkcnz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2astgsnmz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2bttylktf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2hpldurlz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gt2rdcgdrqy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gt2amehsddv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gt2rtgimcuf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gt2skzrbvbn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2hvwerkya.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gt2acsorzwy.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2unizvrfg.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2ohjmlerb.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2reqgiiwr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2gppsrwui.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcjylevr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prsnjrfa.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irztiicw.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2ebrwszrr.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkmhsitz.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2ootrmryy.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2zynnwsuh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gt2dnyouwqs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gt2aafiugap.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhcbyggr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2mqgclwwj.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gt2aupjhaod.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2uhxzwzad.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gt2ykmjafzx.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2czcfrzhl.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2elwsufgu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gt2fkiwxmpk.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gt2diuyqpdx.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2wfupzxik.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbravhnk.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gt2dgtikrjl.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gt2eaynplqj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gt2lironibo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qczrkjia.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gt2mmgnuvvo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2ypfeaxrw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2pezkmjyk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmyymibe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luybspls.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gt2iqnmoerj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gt2quukftfd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2gdnpyjmt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2mfjklezc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gt2kokrrqde.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpknkvho.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gt2plpszpwi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gt2yyipbsok.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hohwoqdj.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gt2nvbafveu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gt2avfnkirj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gt2umbiasdr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gt2mitreiee.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gt2koexiihs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gt2nzrpdumb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gt2pazzrwpz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gt2srvrtjft.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gt2afkpjfee.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wggkfrhs.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gt2qftocpei.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gt2tausajfw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2ftbairze.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2khcbkeld.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gt2fdozxjlb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gt2oyqkkyjb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gt2slolskpa.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igqrtqam.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gt2qhthxqkg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2jmpkndjx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2dfvnnlpp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gt2quthjqzi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gt2scxunohy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gt2aitrlsym.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gt2rdddcwkq.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcnxdjhu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gt2mrdnyuss.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gt2zjthlggj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gt2vnzgucga.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gt2dewdlkit.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2suokkkdj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2arpaxtoe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2ncgjndwg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2idpuuedz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfitfnop.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2qkbkeuws.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gt2ifdrjach.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gt2izdddrbj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2qhidbpwn.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gt2cgnhulbg.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2spxnlajr.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2mdnsbuks.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gt2vmnvajhc.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2wninvuzd.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gt2ufrifiww.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bttfcjtw.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gt2mayuejuu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gt2vvbdanci.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wihfprnt.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gt2mbxhaelu.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2fyucuwno.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gt2vjzwiybv.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gt2zmfuupoz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gt2ultgmnyr.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gt2hflzxuwa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmkddjzb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2dvlaggxp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdlypels.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2prxxlimm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2ozyykutr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gt2uzyohezm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2psxaugli.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2irkxmfbb.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbizjznu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gt2kxteodaj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2fjgflbiz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2pmsfkgyl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2adthdmri.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gt2irhwjkoa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gt2qwlxswmj.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2vjwxaslf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2ewztgljk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qlfyrscz.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gt2ouqttwog.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jzvysfsa.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gt2dzdpetgk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gt2kinofdky.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2gpcixukj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gt2hyawvscn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiblzjfi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvaawft.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gt2clhlorwd.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaevmleh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2rnwbryhi.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2vchwxrsz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gt2htydgqmo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gt2dtmdmrvh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ufpekczm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2deduayxz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2srrtuheu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gt2ldxirapb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gt2azhqwarl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gt2tlssauqi.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2hfsozjav.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gt2xqkativm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2tdsrporu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2lhxhvjfd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2oqlumpma.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2trmsdqdn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gt2jqznxmeg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gt2rsgtxlnw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxdqndcy.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gt2zjstlzsp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wttvpayr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gt2valchpad.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2hkxhzdal.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2ntuhxags.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gt2pamgwbkh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2axhfgzuo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gt2etbiqmzn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gt2lrhvjcry.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gt2dtvucfqx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucokczaf.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2vqqcsvfa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2mwuurwyg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2fopkpfzw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2trndkbpo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2mpipijlm.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2psgnlwlr.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2whkwhgeg.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gt2zhaikzho.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2wjhhtngh.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2ntnosolm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ftjbpzmb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2fomudqzm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2ycwyksqr.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2yuhiblzd.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2dpkaekmi.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2qsikkcxr.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2exipaqoq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2nulvgtlg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hanoillm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2ekgjjiqk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paobocsc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2ldqqvwhx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpruwkr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gt2kjjzcisu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifbucrmk.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gt2cftqbcvq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbbanpha.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gt2vjhyfqiu.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2yyfrkkna.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2ohmbvcfr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzxdfhtv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2eevvzxns.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gt2sdnmolxq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gt2azfwsqvj.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gt2vdduasqn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2addgrtxd.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2adloiaql.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbqkinri.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeoufzp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2kaxcauls.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2vihrvqvp.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rmlamvea.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gt2vwcywkxc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gt2xeumrkjq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xwykvcuy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2wumbrigk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2lwvhcybc.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2gwzurwpa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gt2qdmineju.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2cnacecyx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2dpsknbjt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ihpdoivs.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gt2cvawvjsb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2mbtsahft.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2nvqnyfax.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2okaaiylc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2swgqvtpq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2edsuyanq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gt2gtocymbn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2zbsdmyep.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gt2nsfoobgs.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gt2kzzofgxi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gt2mdwvobnr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gt2ojrnnkqv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gt2yodusvoo.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gt2fkohuink.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2kpnuvsva.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gt2mycvjofm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2mnpboxih.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gt2kkiundel.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ewgkcurm.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gt2tvjseacg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2gxzdolck.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gt2ipdwuxnl.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gt2tzaqnvra.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gt2nqslwajv.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2qvbqsmcf.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gt2dhprzagk.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2hnispxwt.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksvjdvgt.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2rhvosris.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2eyguvjuz.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2lofauunh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gt2gffnzrsn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gt2ijyxjckq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2tfsotgyu.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wvpxljsa.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2imoqrxvt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrvcwdut.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gt2stcifsmg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2pyajqvka.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gt2goyhjhin.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnmuwoax.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2wmhohumv.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2hkuqdkuq.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2afvupach.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gt2eafbedqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gt2luihncnl.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2fyhcxgrq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2zoxhqaca.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gt2tygfsewv.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2cvsjvtps.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2olxmschr.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2iyfnokmi.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2peicttdg.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2tozmfkot.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2asqsgbdz.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2zhpspxjf.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2llcqwmtv.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gt2uwdygsqw.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2kqbqhysp.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2fvxdftuw.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2wtokhrxz.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2rziizqrp.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fhipsrsn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gt2mfcjshiz.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2hisanfbh.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2asjxejjm.html


<!-- 参考信息 -->