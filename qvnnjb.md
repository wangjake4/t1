代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2gbyaqmxp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gt2ivftxfvy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2bkrqnaeb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2mhqikanu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twnbastx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gt2cmaklcwv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gt2rtajvwup.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2ohyejwhu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gt2gnwwzqxe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2vpmawlbu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gt2kbpqflzy.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2viuiaqar.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2ibmuctuu.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2qmgljjgg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2vkygryzl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2nhzpkypa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gt2gaoufikv.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrkdontu.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2iezfrzqo.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2hwvdhpvd.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ughltjas.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2hlrbymdr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2piyrbcjb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnopfnhg.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gt2hidrzebe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdlvwnsg.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gt2pkheigkg.html

Py:   s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvevkytx.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2rtsmspsd.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gt2wrvitybi.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2hkcfchfw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gt2shyijaxk.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gt2fpfuaofo.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gt2hxahunjx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gt2qzvavrgj.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gt2mcxuqlgn.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gt2ewdznhhk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gt2ozyiefka.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2ofmymiwa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2ykytfynl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olrmnbkq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gt2owaptsxy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2acbiojpq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gt2lnwelusf.html

[E14] URL 编码与 Base64
来源：http://dali.gaohongyu789.top/Article/details/gt2eeriixak.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2raqazajm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gt2yjsbyjlk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gt2dvojfanz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2cchglqid.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2ofuucowe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enhhayht.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmqkoapa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2wukowzfq.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naymyzcw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gt2rzobcnyq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gt2nzxibbkr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gt2mzwejwbm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gt2oloakfjp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2juqpmdtk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2usxxbaad.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gt2rafrrgvn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gt2zcoceurp.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfnnyjrn.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2nbqvsbgd.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gt2xaksldky.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2gvquawky.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2kcjmblmi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2qmexygmy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybfnilym.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gt2jwaxabof.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gt2rashxknn.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gt2jzoprptd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzbuknvm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2ndcxjgqe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2pazckohx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2cruqvwna.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2tatodrpf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpvojte.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gt2jeditwch.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gt2jqnttord.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2iiwbqnlu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooflpscb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gt2azypdizi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2ifnzfnur.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2oifcqfih.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2iwkxutbf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkndmuez.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2kxvjmbmd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2ztxforpk.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gt2cvwjmdin.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gt2bfxrkfnb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2dxbyutff.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2dtowaxaw.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2iwqrxcpa.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gt2fwcmnckr.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gt2lfdtocec.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gt2zeporlzx.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gt2jzysarod.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gt2zmktmidj.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2skjfsuhk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gt2wzwijuoe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gt2atgsauvy.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2ryqpefmo.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gt2sytxgiwh.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xctoidft.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gt2zhcgdnjn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjfjivmr.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gt2ekstkwsr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gt2ixuoriyk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2rfqrurte.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2kezqkeqs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2xqjzyxbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2qjbhrppu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gt2hydtmamt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2cdiqjrdi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amipucge.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2zfsohqxd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gt2uywukniw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2fhqauuxi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2ciksdwkk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2nhdyoxxs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2axwohwdx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2zbpdtmip.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2pfxraaxe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2ckmtnmru.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2aourenfq.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2vpjasatv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pqctakvs.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gt2qxcybifq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyhxevub.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2auwyxavr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2faquuzbo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2sellslto.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2sntxifvk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpuyoptj.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2arazqvoe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2ozsccbhl.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gt2aeysybep.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gt2elcplvsw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2lpqamngj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2cnfcjowy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2fqfzoqdx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2nlolgudq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2pbkkulpm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gt2yihmqjah.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gt2jcbwarhv.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gt2smdkhamz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gt2fpmletks.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2sfcifuao.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2prnplmts.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2ixbxvclw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2azzlwehm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2hvgbzqbc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfyewdgz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tpvxfepw.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gt2oxsmmiry.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2desjuoaf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kghgznxq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2fggxqxrp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2uuyskcdx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssjrcsqu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2ihmocokf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gt2fbcwzqbq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gt2wxrjbksz.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekyallcz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2hpxfjklt.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2txbenvqv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2cfqyarco.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2qtitvjyb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2rojagphc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gt2mavdtybm.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fksqjtel.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2lbkchgwt.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gt2cvqlapyn.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2mswgnpwf.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2fxnuzpsb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2olqkpsze.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2acxacwwb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsvdefic.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2mrcopywm.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gt2jshhpcjy.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2guwmsrit.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2dcculepy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwyjlshi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gt2skuivort.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2aimsbxkt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2hfeaugue.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gt2bgwbnovk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gt2ztnhegil.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gt2kbfdkpiz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gt2ryuliszf.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gt2rimhpmiq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gt2gystzzjf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2zozibldy.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2ujcnbqtq.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2oopkcoaj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2vxjgwyfm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2djcuctil.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gt2yxugsnff.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2uqwrloyc.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gt2qbdvrvkq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2xzeqvjtl.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2nvshecnr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2ealnxouy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2zznmlpjv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2inpqdcdc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2yfnzcsct.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2irxypkpg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gt2ywqxfsvq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gt2zeokrsyc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddbffbri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2fbcmexni.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2gkcpzlfk.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2iewrqbni.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gt2ytuahipu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2owavaqkb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2mhxpqosz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2cwjudweb.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gt2neljnltr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2wfygodnq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gt2gddvcdfg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2uwtwvkfg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chxpfdtb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcomkuxc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gt2ipekrglb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2uudczxoq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2afpoelgw.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gt2abvgcnps.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gt2jnyfnvmg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gt2nketwmkp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2dqulmodq.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjzypjgc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gt2kyntcnfa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2sojfhugp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gt2qkjotnnk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkslapke.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2cwgehxmm.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gt2ihefgqmr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qwyshdkw.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2moltpfhr.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtjxijjr.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2xlhzfvlz.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2weeubkds.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gt2jijxbjja.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gt2obciuses.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gt2lkedbsqk.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gt2obqkzgkz.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2kyagicaq.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2eybyfnwt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gt2btzmahoy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjhxwfyf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2qkhsgggn.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmbcxete.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2fxlgmqhu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xykvvagp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2zavtletg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2ppiotnsl.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2cpusakyc.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gt2dpvavvwp.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2hfriqcvc.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gt2gfdmacfr.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2pqebhiey.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgpagvzk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gt2yzxrfogt.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2nwdsyfci.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gt2zkujzyjb.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2qrkzqolb.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2wmyzeamk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2sryaxhad.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2uxjwznsy.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yngiyuoj.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2xsogyjbo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2scpbgqpo.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2unlrrdqt.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2qfzumlqm.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gt2ipykulhq.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2qlycjhcf.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2llotbwrp.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2bwmtyzzl.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2kfirsbby.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kkqjqmrs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlizqqin.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gt2kmofqcru.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2fzvjxkdy.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gt2daqirfze.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gt2zyzdjvlz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2flblzuvd.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2kuetnpls.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2wvwbjxrg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cgnbgxhs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2aiihnxub.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2wqstkgod.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gt2ffdiopmd.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gt2kgeykmrq.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2flxhttse.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gt2xdjpiywe.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2gznumszn.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2shvtbqwj.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2lgsibjbp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gt2cvertwrz.html


<!-- 参考信息 -->