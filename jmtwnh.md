代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2fcvqnmbi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2ynyqmxcj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwqafxlq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2fxuwutgl.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2ucjkqxbo.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gt2hamasoay.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gt2nzcnkgih.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2ehkyoagi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gt2ejktfxpc.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2mfofksek.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gt2uehrkgtq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ukzjjrhi.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gt2jnmfbslb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gt2uyfxntle.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjmkdyi.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pulzxtqt.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gt2jhdxynbt.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2nszdsoct.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2zveltxvf.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2yedqhjxz.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uluhgmls.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2zqxiesmj.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2umdrlcsr.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gt2kyxpymtm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gt2xpwbmabg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gt2prjyphkv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yruzxpzo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2yyjhrsge.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2abzpirpv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gt2mbplpfdo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuiioufj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gt2lidwpebh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gt2ohaeqywk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2fsqvjrla.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gt2cfovffko.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2ylecxpjn.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2kouiuaug.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2ryidvfoz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2rwzcvmyf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2rlmidwbu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gt2gwwbvqfg.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hahkiikp.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2qvyyrcqr.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2kukptnpl.html

JS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2xtuvpyzo.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2nbiidjhh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gt2pyvlekqr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2bbozmvww.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2ociunhdx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gt2boscsssv.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2znvgfnor.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2dvkviicz.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gt2khlvvkvo.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2sjtuwtbr.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2fzmdsrim.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2bflfvbwn.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gt2jfkejgyw.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gt2eotqizec.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2szvshuio.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gt2tkrwcamq.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pijwcazy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gt2idwtvdzn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2kmizvtsr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2sieoewvj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gt2fkqyelzb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gt2eebixlii.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gt2rygodzvj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tepfpgol.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gt2wgrfwzql.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbfmvsh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2qypthaii.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gt2kfokjmwx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gt2dpxqkelo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2msspxpwf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2kqwfnwpz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gt2dycflrmk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2mjqcsqdy.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2dahgyahn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gt2aycecoig.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2yhvqgdvo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gt2ufnxawwy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gt2rldxewlo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2hpqhuynt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrkkysz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gt2fdwcxmyt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2dylpiqmh.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gt2ywnbvlcm.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gt2gvzhniuf.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gt2bctxjkie.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lueqlxmw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2nnvkrzzi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gt2uxnvtoon.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gt2xhustelb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpqatugq.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gt2qyfesiov.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gt2bkyhzulj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gt2anvaigzj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gt2zupwgqga.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2iekgtkgn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teuykwxy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2zzawmqja.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2hzrxiore.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2rmblzzvb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gt2nkaspdkm.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gt2rzvboaln.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnddanpg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gt2nxrbtopu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2zkonvwom.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2zyboxmyx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2tcivmvlp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2ilsloozc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2lyoqsssn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpwopgcd.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gt2cwncvgpg.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gt2kwbltgue.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2tiiacysm.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gt2rleirykt.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2mqlcqcip.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2yzmswpeh.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gt2xqyluraw.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gt2pcclllvi.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrdprzqp.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gt2bvhgfplw.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gt2ppkuohbd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gt2erzmfsbr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2sncebvqt.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gt2ltptemwc.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mbbriodq.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2hohitlsc.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2iwzzksya.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gt2jyigvicy.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gt2atdlrtqo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gt2rpbvvrbj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2nsjnfmoi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2fzzhfqic.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2zzvbynpd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2kglaxlgq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crddtkln.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2xpgackdc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2gdcqtnda.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gt2mgzqlquz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gt2xxdfcoeb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2oxlekqte.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mryusbgw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2iymvnipk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yntspjpw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2rbaplsuv.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2ilmvbnbm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gt2vwtmocmy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkjsxaxy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqendez.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tkcvmsug.html

[F01] 读取整个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxwysadm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gt2wwelnvkf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2xqmfuclr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gt2telawuwx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2yenbzept.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2bcdhpxmx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gt2eurbboei.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2gcyiziki.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2iugemhve.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2vncsfsom.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpduzzbd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gt2aqtbimfg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2tgamwrgy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2vndtkgpj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2otmellci.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gt2hkgoxhdv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gt2yohkiihx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gt2mljbheqx.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gt2kfsvlnnh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gt2mfhwtaow.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gt2pzothyua.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnlmjepg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2tvikknri.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2osiaghpi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gt2rwmrcdam.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2fmapkaqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2jvyfzcqx.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gt2dqmoaolt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2bgnynppq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gt2qajifweh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2qmaeajex.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2xuzvvxad.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gt2vdnjfggv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2eyktrjqf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gt2dolffkbb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gt2thaivdfm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojmfdyfv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2pthmommn.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwfiuewb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2lhmrlbdn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2jcyshrwj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2ccswxqsa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gt2lycdnisz.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2saeddcpt.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2dzpmzqdz.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gt2ounuysms.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2czhzxwie.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2tihpabht.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2spowekhx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqaftowu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2mekuklsm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2rexyflcs.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2guczdriy.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2zxduarvd.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gt2tpeivddr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2tjsmnzfp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gt2lwzwcjin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2gwseroia.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2wgwbhktp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gt2tubaljzv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdtuqjgx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gt2bnvlzuof.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gt2wkqjcljv.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gt2poyhtkub.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gt2gycpamvl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlshhnvj.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2owkjaioy.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2kqkpnwsu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2htcmrfcd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2ssxjpovs.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gt2azwgjago.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2ezpzahqp.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlcpoatf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2shxzciyf.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2drxdcxdk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gt2rpwbvgvr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2lakmkbpz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfsvaiqc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gt2snrggioz.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ectqenxw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdykhkcp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2utqlegcs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voavvcyl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lblgxtrj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2nlmulmpe.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2nsjgmlvn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gt2vcoezxzr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgwcugqt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ihsrwkpd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2hwttybdw.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gt2fesxhjxg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2eyapptif.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gt2ewjeskkm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2kxihahqb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2unpjkvxe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2dajwqnsm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gt2ticaoyvd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ewfkifvs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gt2kpwgpppr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsqwizm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgippzmr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gt2ghmzttab.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gt2sfwpnqfo.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gt2ffcntxmc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gt2wxffqixj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2hljsckyt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gt2oegpxzos.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gt2xphigaoj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2yxpdkneh.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gt2bvhveyzi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2udhelawo.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2iujrzrbm.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gt2csqcfqjs.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gt2tqmyauwz.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gt2pedniebg.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gt2ypzyvnwv.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xzaxzdqk.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gt2qvaybtzw.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gt2qbcybdfm.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ridmkgld.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2ccdxeyyn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2zkufxyrm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gt2fibqoyue.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2obvuchez.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pwhdsdnr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2sqjelckq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2qhbbvngq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gt2jsmdysru.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rlftcvwl.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gt2vjbhtzfa.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2lfopiuxz.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2oxmbqoxr.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2zkrgafed.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2rcmcnceb.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baxarlqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhfknqrb.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2nwiqdqkd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2uxjwgdyt.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gt2wrlitdwu.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2zwujiqym.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2giblwlvd.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fqhmfkdm.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2wnupvbts.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmkijhaj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2gyhuxtce.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xllkmmin.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2plzpckre.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gt2zbojaztb.html


<!-- 参考信息 -->