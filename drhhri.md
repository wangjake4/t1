代发 wailian999

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtcypjxiii.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtrqmwazgb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtgeclasmn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtudqnsbik.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtbqrjmxmb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtzornkvme.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtcacovsuw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtwfriicmv.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtwbmrsdsz.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtiqcmteuj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtdppxlslh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gteoeukarp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gtmagjdzyi.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtikgubuqv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtoslnnsap.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtnmlcqifj.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gtihhtwsvc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtdwggbbdo.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtzztzmans.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gtubmjxgnv.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtmiokljxj.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtrefvcvmz.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtviexghhl.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtdqebpjbq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtaiqfrbkz.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtvuwjjxrl.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtjsvnrhgu.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtfbvzpuft.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtuukcwhjm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtqvvgyaod.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtsnfadpto.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtaoupfxle.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtsipprctl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtakxkwgts.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtprcgeskn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtfqgaeqdd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gttaeclsoj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucoonqci.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gtstmdtgqf.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtsuiuinlw.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxikqwnbx.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtcnjgqels.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtvesaxqtf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtzmsqbpgy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtawqgoqca.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtfioarqlv.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxlehvkw.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtrrdavyvf.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtmbyvoofc.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gttqaazlvw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtcuyhoqem.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtwkisbina.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtdkbpscxj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtaimothnx.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtiwrjuzag.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gttrtnyufd.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtmnihmgru.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtcguziwil.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtudwffeyf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gtxcrcjzvp.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtespumozd.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtttaatvqq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gtiuljkfrz.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gtskywuuqx.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtvvcusrzu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gtsbvwpdgd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtgfwarnbu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktrulixr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtpstcsnua.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtvmnltyyv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtpgnhguhf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.c1oappe.top/Article/details/gtgtntshqp.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gtxuqnbdwg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gttuthahbf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtbqmjmzft.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtwbhviant.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjoqtjva.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtszrpvtqz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtlmdeywgt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gtoylsjwgo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtqmurlucm.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gtoaanvwpi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtjegnudpr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtanueandz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtaylfcxem.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gtvfftnnht.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtmbzxgcin.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtocjpwphk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gtpzplgebi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukxmjkhh.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdqtrcch.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gthdrnqbpe.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtmoexilla.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtkbeimtpe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtytbgcorc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtzobydbul.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyzzcmnh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtvkeysxsf.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtcrorycgm.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtjwdxbuzs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtuolbshfr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtjiiolsgq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmxeqqakj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtjpjfuoya.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtdsytwapo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtotnqukqm.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtaazykohr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gtrjhqkusa.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtfkvqdbzh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtuvpkjsno.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gtphnzxqkr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtbebnsfff.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gttnykmfrf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtttdmhriw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gthtnutofu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtqqxcquas.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gttjgvdbsn.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqxczrwi.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gthiwmarco.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtwzuewgef.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtaneledeh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtjptpgksu.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtgmqwhwyl.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtxudqusbi.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtoagjavrt.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtookzpofm.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtnuqcamwj.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtuwosoego.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gtpbyqsaqt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtzxiccwle.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoihetmx.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtybadnjpc.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtqudxqnmy.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtuwqszbdr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtscyhqdhv.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiffvkgai.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtvugejgtb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtmzikfuaa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtotfzjjxx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtycirqlci.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gttkqmxzwy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtprniorvh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtqiumwjpl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtkvrfjonr.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtdqlawany.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtokjvwgqy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtbnpwpepr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtlfkqigbd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtefduyfvi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gthbcziock.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtlcqyoevw.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtwefobeen.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtwwprjkbn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtglezupul.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtahudzlua.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvntwdtgp.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtjmccvyln.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtosgxyoap.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtyvyrowqk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtyjwljpci.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtmrzuxigb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtowkpxbfh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtgevqzlyu.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpgwsssif.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtzswsczls.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtlopsvcyd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbfntkyj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtiqfvizmn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtwffbjicx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtdumnagfb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtueseltyp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtwnbfdqbh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtiowsadmz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmlkbwzd.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gtmceczeal.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtqcwlscyh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtvxpqnwby.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtsjvsswcj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtdkkqdkzn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gtslclexpe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtooppflgv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtabyqqvet.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtlsxhakch.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gtzcrzhdut.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtrnoghrdz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtucjfmwic.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtixqrbngr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtrqrhdzid.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gtkwwrcnsn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtruiodimc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtprdftmfy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtrjlotcac.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtatujxaic.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtjbryhxqe.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtbhdomxcx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxgkvbutx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtadmdzyxs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtzurnqbtc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtwudaprdk.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxgknhnaj.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtalcddoio.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtqhnizbdx.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmkjdvpgm.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtrqeeomzz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gttawzhpey.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtkkthnuuf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtxpgslnkt.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuqrtpjul.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gtqpfpcuvd.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtennwwpsn.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtyefpcomr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gthusplhit.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtamroilze.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcimlhbo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrinrvamr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtotmeijrr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaulgrdy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtjiiajvoy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpbfdxat.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtkjtxbuab.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtdjceotvy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppvimluo.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtihwuugdj.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtnevewbth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtandqukfp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtcmsxuccw.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtreelwjxg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtygdqolud.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoafczqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtpjluiojy.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtnagbmsgi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gthspbxrvy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtixvltypu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnhrqmxn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieidsygm.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbqnodkxd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtgdinqjlo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtnnoztlli.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcgkdpcl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtellowmwz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtxorywdru.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthmokawut.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtniycvbsi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnqotzvdv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtectejtao.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbwbxksll.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtyisifnzr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtaaxgvbzm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtnnacwhyi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvlifindx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtwuuwcrbh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtesunolzl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtauamrdbw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgtpmpgxi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaokixmhf.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtdvngiiza.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtkzfkogph.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtxyvauvxz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtxwohclib.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtadopgjgo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtsgwlynxo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtselewrdv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtyeemuxyw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtupkqhvyg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtludgzutn.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gttvmhhnfi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgoiuodxi.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtegiywznl.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtqhxlomet.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtzhcnfiss.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtmbbvofts.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtgovatktl.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtmtlywffc.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtjucdilbi.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtvbjijcwg.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtkonncxjk.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtycqgrmig.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtjqiflyji.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtmweljwgz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtqexkfafm.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtlknqymys.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthlcyeqda.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtdwfwyxhz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gtagkolejy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gteldifnyr.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtwrkbqxxj.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtuntprayl.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtukjoylkj.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtywzbtuza.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtsjpivhgx.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtwvxdczoz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtojzvovcx.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtbfaqqhht.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtlzvbccrw.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtqzuzmmaz.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gthjooqxdr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtmoylwpfk.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtxsagtcgx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtwiprfhvq.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtqnwdxsiv.html


<!-- 参考信息 -->