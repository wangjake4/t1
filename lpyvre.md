代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2qllgoipg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2agkvubzo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2xvoqnqpz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2edyknwtx.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2bkwrojis.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gt2lpvstvuz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gt2sqjkesup.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2ndacqcbm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gt2gqrtfmlq.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gt2wrmyvyld.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2zthxwqxk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rymawuam.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gt2wgihmyro.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gt2lciavzyj.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gt2qcgcbzpp.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gt2kiiyprfj.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xocbffzc.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2ihlvtajl.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2itizgifn.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewaubxqm.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2sjotxpiv.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2svgaoyhi.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2cpuodtto.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2roavyzjc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gt2ininsmft.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzkqlpql.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2doqfkfsm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2biaupqij.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2hamwagbb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gt2mavqbjbo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gt2rqschbdl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gt2tkpsasux.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2ymeakjxx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2zjynatnx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gt2gmwatghs.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2wvialdoi.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2qnsqfpvt.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2lixbltyg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2neipdypt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2lzrdassy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gt2smlcxiba.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gt2guydvawh.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2nejmulou.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2pvvrtbdq.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2glzrigmw.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2icohfxja.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gt2knlcfhyv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2ywqwmhgx.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gt2rvtfojgw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2epmkrpkv.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2mjhqapzn.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2jgipzysm.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gt2sftwfanf.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gt2qdfwjtpc.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gt2tgojdspy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gt2augueflt.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gt2hndbrgly.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2xesqkcmk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gt2gksexegk.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gt2ffsovstd.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntuuopuk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ehiquwyi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2wcyrqxmv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ixmyogqd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2ssntovml.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gt2seuvysej.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gt2szbxntvx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2grukapur.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gt2yjhemeuf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gt2kvwzgaha.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gt2atkkuync.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gt2ilglhsnt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oipvtahp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gt2kbczkwyu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gt2gzdpkqsk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gt2gbxdrkwn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2srcuhbon.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gt2goosmiti.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gt2kcgemdui.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gt2nrlvcsue.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gt2ospbfsfd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2fyhlldop.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gt2iurctsnu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gt2egpascux.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2gvemurjo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2bdbrfhem.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2gpjhrnyb.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2tduoyify.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gt2nvtbuuxb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2jwyrfbjv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ribphhps.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2hvfziuvc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2mfwkoebd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2cuwcaatz.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gt2ssfpklup.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gt2jrcommds.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gt2cgeuelsq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gt2tqmdximf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2ntxpydhq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dimnzuir.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuipeufw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2rqmqdwzm.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhaofgin.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gt2bvcjauxp.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gt2uvkdibnt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gt2yrwkshsz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gt2orrybaao.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2ngplqscs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2pkwkdwto.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2zgmgtsxo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2zqzljxjs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gt2qxidaupi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gt2lwvjqrfa.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gt2vrhfzumy.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gt2qfxzuoun.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2indmknbc.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2nxygijwj.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gt2tqgrgiak.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfijggmy.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2xrjqxroq.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gt2govrbegi.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2uocwxjlo.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gt2vlhpocjz.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlseppsn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gt2swbqkwho.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gt2wcqilcee.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gt2bbjzyrpw.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2inamuqju.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gt2rhogxbms.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gt2hbkbegno.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2aewpcacs.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gt2zfxlskni.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gt2baqbjsye.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzqqqcwt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2cpypxcxg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acorhgbk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2xtxxjcfh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2uchxwajv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2sokrkdun.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2gumqhvfd.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2poshgpdi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oflmvbmc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2lmnikiub.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwvbxnhr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2gjwviqrr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2sqdtvdwn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gt2ywxjmlwm.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2lzqrnudk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2bfqtsyso.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rexhvpox.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqolbwad.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2tgvobuwq.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gt2ktyentgb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixqjheni.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2bvqmgcfu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2irpupizy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2qfpmlecz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2qzukvwuy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gt2wtgvvdvk.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2dcfixqdl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2qzvwenpv.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2idzotwuh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gt2vskevbup.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gt2zqdabhns.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2yxzeyaqp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2xezmgulw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2itkugzvd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gt2apiwefsp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gt2haiiwspf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gt2vbxzqmju.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gt2vkjytpud.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gt2jswaguuy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2feukeyvt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbhnvtss.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2waiyqigy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gt2ybspklwm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qojrplgp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkuebsqp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqdtfzhy.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gt2clbmwkaw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2vycbeajz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2uycabmzn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2rowaeydz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2atjczayf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2wrymgska.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2bprrceap.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2pahcqecq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gt2usbfsobs.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gt2qrcvnsyq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gt2cuzdwfto.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2bosdqwrn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2crjacgui.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2nqxnpwlr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2dnezcnog.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzytuvcc.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wucttixi.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oovonvxk.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gt2yiqdmdzh.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2yzxekazy.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2fiyqddoj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2rnlvxewh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkejiioq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2lweejozh.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2huptfqqr.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2snqxylpf.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2eozjznqk.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srbimskp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2tftuzzce.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hygdcktr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2hrefycai.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2woogmqzo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwnbgovy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gt2zodkvhil.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gt2zscowwwj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2uzwjejvl.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gt2nhdylpda.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gt2seqenmtv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsqnmyie.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2lsknkzng.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2zgnzscbg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsttoisg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2drumhcqt.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gt2vhtsidxi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gt2mxqkwktz.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gt2zcrolosl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2iuttdsdn.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2uwjxgldh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2yabwtknx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2uxpvxqpx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2jlpmavtc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gt2ovnmdhas.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2skadrhoi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gt2sbazedqr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gt2ywlrdbyk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2zowvqdnh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2cnuhuroq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ymxilfts.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2nlmfhfmm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gt2pndoapph.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2cyxadqin.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2vdagunfp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2qctglkxi.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpstirnd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2kcxifhad.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2qevrmhst.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2dkekinem.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2cziwptdw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2kceuvxum.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2tgdtrsne.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecfdzqec.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gt2bavjpfsv.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2smupdvwd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gt2xbrcwkht.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gt2oajucjzi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2ubzasfrb.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gt2ipytqxlb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gt2dnprbfdd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gt2wtchutdm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2ghqireag.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2myqwnjuz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jpkwsbbb.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gt2dukgqivi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lynqqpak.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gt2wsnuhajn.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2xexmmbun.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2ettdnzov.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2rgrwsbcj.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gt2iuukzfmu.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gt2ptcbvusc.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gt2eeaoauqj.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2kkjqjqlw.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2tseenhey.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2zvhauyfk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gt2agwkbqpc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2mrzwwscu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgwbkism.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2dtwkutkl.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2xlzveehj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gt2heiflrcg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gt2vcoenlzk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2afqvrzym.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2vkbpaqos.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugxaomsx.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2nprqtpwg.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2xrzgvmye.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2uqwyawxb.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gt2xfhnrwpn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gt2ryxukcuq.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxphrqii.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gt2ugvhhvgl.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gt2leseeltx.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2fbcqmlni.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2dpuuwwcd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txlebuns.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2itsbhgvc.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qkzrauvn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2ojbdmqre.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2zeatxxiv.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2sbtruckb.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyipgelx.html


<!-- 参考信息 -->