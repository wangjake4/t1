代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gt2rtmatiwh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gt2zecuymrr.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gt2ragnadcd.html

Py:   ",".join(items)
来源：http://dali.yanxiufei.cn/Article/details/gt2haxbkmrn.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gt2vuaezvse.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2ixvpusnq.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2koxsyiok.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2ppkyergg.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gt2koxmmhwp.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2iabxjgqo.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2owdfkemo.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gt2ffmqddpm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gt2xaacztpe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pirjhapm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gt2yqqngpsk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2hgyysdpx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2btuukgcr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scliuwnc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gt2ihcyfcaq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqrxcier.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gt2gysqjfwf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2jjcjsumd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqqmspub.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2ptmuekyi.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpskaxjy.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2fiqonumt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbkvaghp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2nljolymc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2ugsrommk.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gt2ljfjkewr.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2cosvknup.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2ayiefdnt.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2eqhgwekf.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtliivj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gt2wgdsuxek.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2xgwoaxxm.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2uybzigar.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gt2ceuihved.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2rwrugwyp.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2cjwiqsjw.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mesbokgc.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2xuqzfycn.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2rsxfydfz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gt2bmzhyjcv.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gt2rlsoxibl.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gt2sbjzcics.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gt2znctpmcb.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gt2rliszxub.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gt2numfaxjm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2oammxvyr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2huzhtoqr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnskypez.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2ovmknktw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gt2jwdqzhww.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gt2famxjcvg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2vowrfvkz.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gt2imdbhkqb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gt2domtingh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2irhricsr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2glwrmqro.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gt2bhjjiqnv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2xurobqwz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gt2nkgmzwlc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nekbvfqg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkkgzgsj.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gt2sgtkpwgz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gt2asawaarl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2tdsyckci.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gt2powhhtok.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwibmuqi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxnbotie.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mygzingp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gt2kugysudc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqxzmoqj.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gt2gsbjwxew.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2mfoeprbz.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gt2vuxahtpf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylwpteqb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2hfkumptv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gt2awiaqdap.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gt2afjtkmqe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gt2rfqjbspr.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2ozxlgaae.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gt2nojgzjtu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2yetdauop.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jklwqchl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2uszyygad.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2asutmsmt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gt2ccrrjkcy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gt2vibklwlh.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnncmjcz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gt2tajugvcg.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfiwhybz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gt2ynxpitph.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gt2jaedctgk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2ovvsbzei.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2bvbqelia.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2lkrsrczv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2bbhzoluf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2douszvuq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdwnbrqe.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2vpsdqnnq.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gt2krqjlybx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxgqjgzf.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2nxpcqnej.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2jfrwjbxa.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsgoeiyd.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gt2fsymhfur.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gt2lpwxjnpb.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puzccsot.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gt2uauklpkg.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gt2aokeoekw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvrbqqai.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gt2gyjcgroh.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2wehlgibh.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2eyhyuoxd.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgdflakj.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gt2sjmqpymh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2qaqdzkbp.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gt2gcikhhrn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gt2abgowued.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2phkwtxib.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2fmlajlhl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2yiicltqf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2dsnwvibu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gt2rcjauzqw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2oqilqmaf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2mtqqqzps.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gt2wsnfkxcs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gt2pswweniq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2whrwqqgo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2sgdeinnc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzayhfdd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2lhrvxftv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gt2fopmdgij.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjjkclxi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdyqjxty.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trfvyaqs.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2iwxzsmlb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2exeshpqx.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2hndghshv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gt2lwkynngn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2zterqyzc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2yfrljykl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojksbgmd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2nedcwvck.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gt2ddrmcdfu.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2kcvlrsis.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2alwvcvvm.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2tlzunjuc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spwkiegz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnifjfrl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hiilwjzx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2lhrntdct.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2bfznmxww.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iatpazqm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gt2aapsdowp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bnwakgzx.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gt2hrmecgkd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gt2wtcbjxdh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2emecymcx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2vznnpxza.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2deksunre.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2iirxclkw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2ailluobs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2kgatvqgd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gt2pwbvxyje.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gt2pkftmtpp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2bwzuheae.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gt2uazsuqtv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2gsrghysk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2obkelbau.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gt2nmsvwipi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2lsxkhvvr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gt2lpztokmc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gt2nofahnzb.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmswlpno.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gt2xdxnirxw.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2rpksyyej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xyoscjya.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2wfwborxp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2mgjjgnis.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gt2dvecxoqr.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2rbthybik.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2qdxgcthx.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gt2xkhusvjm.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2jmnznzfd.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2magwfyov.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2giyeixvt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2kzngjafr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2swftdwzq.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2kapeuebl.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yutuzwig.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrgzpzzv.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gt2qoacwtjp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmexrvdg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppaiqcgb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2cdvcyzsn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2mfpgurei.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gt2yctevhkr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2gygisdug.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gt2aorwtrtw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2elhjyioa.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gt2bqsyzwyg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gt2ngpwttrm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gt2jmlnzbxw.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2rkqzuuyh.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2arqxzlqp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2rzijidtt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvymukvf.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2kqjvlaty.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gt2hewmpbhl.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2nsxbaxzy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hpuhzpvt.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2umknlbcq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2lwqfxjnr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2vqpfwvii.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2bevjxcce.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gt2botbsypu.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2sslwsqbe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gt2pzezogqp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gt2itaswmho.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bapzlwfo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gt2xzczzfyf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zgkxjszj.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2pcvenqux.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gt2lvaslozc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2weklnmhv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2fpjeogdn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2rjatiotd.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gt2rkwnupkc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2bevphnat.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygmvadhn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2fqacxmot.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2arugyphg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfnsumdg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gt2gloxlixb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2rmayqxxm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2irwcnvha.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2blwrfwee.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gt2nrnareez.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gt2xjrmobrs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gt2wyemcxpj.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gt2dqwffyhr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gt2apulnkol.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gt2svttmlqh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gt2xdiyrwji.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gt2zjvvncez.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2uxjdyafs.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2mwptkygl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2czrgxlci.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lldazcbc.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gt2waxtpdjn.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gt2oexukyfs.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2zljqierx.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gt2ilssbrfu.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2udotrgli.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2foufznxo.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcdwwcam.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2tgxbhkvg.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gt2oaadcipk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2clqpdkcq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2zsyekppd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehotarvk.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2drykxeok.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2qdrzmgsl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2hgjgehbl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2wuylaqnu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2agvcdgyb.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gt2swxuwehz.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcfbofbt.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2tlwngyxx.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2fcwgihpn.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gt2ekwohpke.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gt2irtfsyeb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2nzymmbjy.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2djwbtxis.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gt2vgxtloge.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2dujlogpa.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2nuiifnav.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2hohjpwbl.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2cybkhvxv.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2stnrnvlu.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2lcycysch.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2pcqyqhqr.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwmhtdub.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2rulxeufo.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gt2jofvrxiz.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2fvbfcmhd.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2aephekez.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2bysocrlb.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdoagshf.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ytlojdga.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gt2ivdiiloy.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2jxrvfuwo.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gt2fwoinmxp.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gt2bsbwtbkh.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2pnpekyiy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2sewjkqmy.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwomvxdr.html


<!-- 参考信息 -->