代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2qbwswakz.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gt2kiytqgkh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gt2qykisttl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2runidlxf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2icnkiykg.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vscrczov.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gt2sqpampus.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gt2lelvfdan.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gt2sqekzuei.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gt2mjtcshvc.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gt2qrjuesak.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2sxctawls.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gt2oflumpbg.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikkylmca.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oayxdbow.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2eilvhezk.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gt2xnendwwj.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2jtpdwjrp.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2aksqfmcq.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gt2ttwvdsfw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2phvqvzbw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gt2vfdqaiga.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2ddniarjj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2sahkxoos.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gt2hlaavxor.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gt2tqxqdncm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gt2exnjcbtx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2nythonuz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gt2bmljyxuj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2pfofjbfw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gt2ffowteoo.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2gxkoqixn.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2xyyodkht.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gt2rggtcsxf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2wbtpttpr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2zbkvcqql.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2pkadlkff.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gt2eiqqxdgb.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2enyzskau.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2ruhmlsby.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2mykkpvdu.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2ffidviup.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2opboxszg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldpuacbx.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2hvgnvzht.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gt2cymlnrgj.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2vrxkexrw.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2brmqulfk.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gt2hwetoild.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gt2cbwnwjqa.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyaccrz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggleghzd.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gt2spdnqbic.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2mhkcxuci.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gt2dndbfpng.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gt2sjwrvava.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gt2ushgrigh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gt2onmakxqk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2gfkppldz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2jfydayyd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2nnszxclh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gt2hnvqyppl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2bgrvwjwd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2iguytoui.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gt2iooavuns.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gt2jmfyalaq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2apkxqqfj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gt2rfufavze.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ffmibiyq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aiornuid.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gt2szvbazvx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2hvqoagxg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2xgqiwfrq.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gt2hsogqsxi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2eczrfrrt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2damgzwid.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gt2hyfqbgxf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2dipuhxyt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuqwiimn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2stiwhhbh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ucslpygp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2qvapvwvc.html

[E16] 数字千分位
来源：http://dali.tanke756.top/Article/details/gt2azqukeiq.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svshoqsr.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gt2hlugawdb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gt2lgztnkvm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2aisdlxfv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bipvqumg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gt2fsglzpvp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybnhcqpx.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gt2xwxjsmsm.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gt2nbuowlbc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gt2iwsnwfmq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gt2prswdsfz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2nhiampao.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2ehxgmoiq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gt2qbsggsvu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2rnaoojcr.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2bfhcemah.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gt2ngvapqrh.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gt2gomzcxur.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gt2vezaxrrv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkhaqynv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2aqtcvxed.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjxdcdna.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2cwufcqtv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2eugyibdc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2oqcxipoy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gt2akggzhvp.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkobheyf.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gt2pjzaakju.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2hnnsmqpn.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2baiiytbm.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2sgmcrbii.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2blqvcstj.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2auzsnnes.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gt2stmaamkd.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gt2cxghcozk.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gt2acaojech.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkndpyfx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gt2unorvpku.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gt2oryplxsl.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gt2drwruzci.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2zadxxprv.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gt2yxtlbkqw.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gt2toqnhhmg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2stdhtoma.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2tbvvmttr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gt2dojaxxbi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2kvgvtigz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2wzhovejh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2zbbearxx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2auuxonjd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2oyoqtalk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2dyyxmfqx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2kynqcrmt.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gt2yvxzykuh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2owdecrbs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qiwlzmyw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2xgxyjrmi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2uompzdml.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xejcmfwa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gt2ywraojgh.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2hpdootud.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2wnevdshx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wrfeqpfu.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gt2nxmwlhoa.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ezmwpxhd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nctpkhtz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gt2srcugkar.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhgrshlc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gt2syjhorew.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2cdvhwcfg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2eiuolibj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gt2llybjpyy.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2grachbol.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2uqugfazj.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gt2vqipiwbc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcijtwuy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gt2fvzkqtwz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gt2bjidcxxu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2titbevpo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2djilhxyh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jftjxsvl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gt2tttotzci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gt2awpvvuhx.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gt2gtzyrifw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gt2mvybvmag.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2utefwell.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2yvyncryg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2iuxhuflv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2dahhkhtn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gt2qnbkgpdt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmpkitnm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2ywvwcyfi.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gt2kcynolaw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2fxloalxi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2qvcemibr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2fsculvfm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2vytazemm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjinyqjv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2dyrztgas.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2mvnqrvoc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2dhagfyod.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2jkumpgpw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gt2fzvgjyxu.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2jorplwpf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2bvqwueug.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2xwnpiecn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2pljvzhyo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gt2jlvlprcz.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2wbvwoksf.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2fxxiayjf.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gt2tvpdsvst.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2itntvwka.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2bcvhyvav.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2bkdizyue.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2sdbjciaq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2uivfdvbq.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2pyfebwzx.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xogadkwj.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2lpxsxiip.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gt2kiiawfjt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2noxgmjgx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gt2wqgmetdv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2mmepapap.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gt2cxzzvnur.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gt2sipcqmrt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gt2djtbcntw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2ctopiptg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdfjcoaf.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2bjrwgawa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gt2brxmjcxo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2azpseezl.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2lxpgbunc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2bkfirdti.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2rtegxuek.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2tpelvvau.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2poyvjjbc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2lefthiuk.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gt2gplbiaiw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2gauikfcr.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2lroytppr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gt2ejicescp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2vukbvpet.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2mipzmcgw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gt2rvvymohn.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqjvkzet.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gt2umsngwor.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gt2eawflpvv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2pmptwiys.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2pojkgowr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ksyclctk.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2nspdndyq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gt2yzeclvnn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trowhiwq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2bobblwvw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2tcalzdko.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gt2ycoaency.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2kxrzspyv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gt2jrmikxtq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2utfwvwxp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wjsdydxe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2hsaxxhzn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gt2cpovkazb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2izlqhbfm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xixjovrn.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2oepenixl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2ssizohrv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gt2ilamvzkg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2atfbsixf.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gt2duspktru.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2mbktealt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwvblusz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slsmgvei.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gt2acckasyx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yjaquosl.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gt2hdhalslh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ndibopqf.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzfxygdz.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gt2ilpqqgdc.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2fbzxdavh.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2gifdpawj.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gt2ebgrsdsr.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2vvmxhirm.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxflqpzl.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gt2lvmljjiz.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2bfirvlan.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2qvumzulg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gt2iogpwvgj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2foequvpr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2cuqxqvax.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2qaivbadj.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2xgiklbzr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gt2sxenwvxc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2crqssers.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2flwldmtm.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofdpggym.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2aowqeoye.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2lnxpzgaj.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2ufespcwa.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gt2axwlzkwn.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gt2xjjcynti.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gt2tvnfqxjc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fegcaybs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gt2dxurxldr.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gt2pcdofqim.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2fccwgkcb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2sgmldinn.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ewjyvhrq.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2lrrgjbmq.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2sjaeywix.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2orzugcwh.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2ohftgiip.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2peuxkbwn.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2bulcrvwn.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gt2uapzqgco.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2zfelzhba.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2tgoxchip.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyiprjeh.html


<!-- 参考信息 -->