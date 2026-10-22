代发 wailian999

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gt2cnobqxgd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2uldautsm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gt2yexsexpu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2syllmtxj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2qgzuhlck.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2itlakocs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2eykxxxpd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2kvdisrts.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoevstke.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gt2mgkybvry.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gt2nqwmwfuo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yggtghpv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gt2nnwislmu.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gt2uqnjsijz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gt2nxqnwycr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gt2fvtesdni.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykqypnlv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gt2algixdnt.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gt2wgfqxtbq.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktvquhls.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gt2qouiqtdq.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eicgtmgk.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swimxwdd.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2vyfdclvt.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gt2binbxrfi.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2wjfsdndx.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2vspoyfnm.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gt2qrjniqcf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gt2qkyrkbxp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gt2fteyoocl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2jwyvpdak.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2dzjrlyph.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gt2amkzzsqw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gt2ogwslwiw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gt2qegsqawj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2wjijrgeg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gt2qsnjisbw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cffdnkif.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gt2vlirtgfx.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2umhkijxb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2mkeqnqdq.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2byppkvdb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2gtgabkiq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2npaasnvn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gt2uxtukkgy.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlwwlwsr.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2bevfljre.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gt2djwvvmpx.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2jtlmlyjl.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2uxqwhxcp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gt2dbyetsxx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2zaemiisq.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2hnofwjqt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2uqmsmeze.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrmzygto.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2uaicwvtx.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2inwludke.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2gtflzwha.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gt2xjmjxvmr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvjntgjb.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gt2gzpkwglx.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2vcemyeiy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2igpypaac.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbhaqehq.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gt2jzyvjawe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gt2edhlsulp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2jflpwsyz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2gjstnxnh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2dviwaohd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2quvuhrfy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gt2bacwqhzw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2zbaiupvb.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gt2aqikhjlj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gt2xdxerxap.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnhvztiz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gt2smxjllzn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gt2oljsybfa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2mlymzjjc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gt2uzlpsaya.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2prrrjdcl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2ewkzqtzz.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gt2nykkhyll.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gt2qfepopvd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2dftlxkln.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gt2qhbdnlpu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2mutfkcyp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2saujydxf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gt2ywzbuouf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gt2zhwzyqpl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gt2nuvkemba.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2bpaikoeu.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gt2oknzregg.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gt2zovqagwc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2ogchgccl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gt2beopbeuw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2cinfotxe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfxvfnpb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gt2rfmtonpy.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gt2ewitbvjz.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gt2mrobunet.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gt2dppnvvto.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gt2cnvdxafm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vquuebds.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2lvteqcjn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gt2rksmisxo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gt2cjffwsla.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gt2oucumynz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gt2ztnocjqw.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gt2akncvvbd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gt2chbsmesr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gt2utyupbge.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2mewdwkgd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2vtuggdrd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2teqnlcpe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2tehgcxlr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gt2mzhnwlus.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gt2odxmoqfn.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gt2qyzwhmyr.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztmmqjvd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2texjenom.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2oiifoqqk.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2wwntkvqc.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gt2jfbtusvo.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gt2ossekhxw.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbubeufa.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gt2bzbnceum.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gt2zjcnygyl.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gt2ilxpxsbf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gt2zhhkhxme.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vgaamykt.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gt2hxrbrqvq.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjupcbaq.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gt2uixjtqlq.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gt2whquzndx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gt2bfmtupyv.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gt2umqgkdwv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gt2imasxpoe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2emyutqgp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2jvuoyybm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2vqqvfofw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2hcurzoyz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gt2fdptencw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybwldmuw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddnutthu.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gt2wavmjyti.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gt2toztkgma.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2darzkqov.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2raviccnt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2inxlpdqf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gt2xgeyqvuk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gt2gksuobni.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2kcndsxza.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gt2fpqedxyb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mpcmoded.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gt2hbffxzyz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dathhach.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gt2btqxhkmp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gt2nhvkhkla.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2nphfhciq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhbydzag.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2xlvyooyh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2lxiqrcbj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gt2fruauzsr.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hafjnmhc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2alckrsvh.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vchewius.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gt2zqpiexsh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2vgtuahhc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvnvnpz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2wfvlmuwe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2biqhuwad.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gt2gghuptei.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2tlpcsxyl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gt2jkokfozm.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gt2fmzmgihv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gt2vyufktgk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gt2hcvkmqrm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2xyrbupwd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2znofgnrd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2wbjekyll.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gt2siugfgpb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gt2qjwbyqhh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2zpwvqbsa.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gt2noyorsyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2vyhxrtxk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gt2srvhibcn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2gwkkldsm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2flkawhqh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2koheuqsm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2vqdgqknf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gt2bryprbud.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gt2ywzspnpq.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gt2lgxmqeva.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gt2ihiudgkr.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2coswogge.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2mnrnzvwe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2gpogzpmv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2skdqbcya.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gt2xrctjyyo.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2nybzxkew.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgsmntmj.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gt2wifnrwlv.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ydkdmfju.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2kkxjgcmk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqpxxxbp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ilesghqe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgybflpl.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqlovman.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gt2sonfaraf.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlvhhohk.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gt2ayblbnmr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gt2yqlpqtvz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gt2fqofawrp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmpoltjr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2jobbqeli.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gt2vodfeues.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2mejwckip.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyoqbnri.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2rgmeqsyl.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gt2ueasxjrl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gt2qscpzzep.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gt2rgpntxjx.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvgiypbs.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2judoxtyt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2wfsjebnk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2imiqvdkj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnpxdon.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2druiojes.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gt2yxozuata.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2rzshrtft.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvpegsmr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gt2hbnjndub.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdlzjznj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2huhddedp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2xxsojmjg.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2cabjlxby.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gt2magesmyq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gt2nckejkjj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2mxdgoqsb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2dznsxvch.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2sfkhjuct.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zkkraqcx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2lmnvvhck.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sspiwmgk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2pvxswnda.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2swhaoeor.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gt2ixtnueay.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2basuqvcq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2rtjbafcs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2omfqrilb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2zoreqbpk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzmytteo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2pshiixfa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2pbamhhkb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2mhzmfyaf.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gt2znktihuf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mirqxcsg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gt2ammhfibk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gt2rfxcspra.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gt2jtjsuavu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2xcbvvjfv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gt2dkbmoogn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gt2woblxfyq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2bzykuhbq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2uzthldcn.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gt2vnxsrhhm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owtnizds.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gt2ufvzxgxf.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gt2mdgxrfxb.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2xwjgpprd.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2oihyjwjj.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gt2idgpxszf.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndfkmkmw.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gt2jqziebrg.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gt2kkxxzhec.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2csunzouj.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvprjlmx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2wmrqbahx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2fxwcqwkr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2cwycprrn.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2adisfayi.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2ffywtndp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2ctvbpxkg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edutsopy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mncuudkv.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2wfsyurub.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2fsgvmaag.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2xlvncavd.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2dujybgqg.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2xctxdsgp.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2coztiqqx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gt2axlhwiij.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmzjkgxs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gt2pstmiepb.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gt2itkysfvv.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2zhfgvpqu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2vtlzvmya.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyiqoawj.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2dfiteqiy.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2fkigjpam.html


<!-- 参考信息 -->