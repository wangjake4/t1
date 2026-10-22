代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gt2lwmbjkiq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2pypkopgw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2gbvlcigh.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2xjcijbrq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2twyazijn.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2spdqmved.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2ibbnbfbn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2imafxaia.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gt2tupvhupw.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gt2hoxesxrj.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2ktnstwvm.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2ckdzlnjk.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2mamqogxp.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2eixxnrcm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gt2mthdbqry.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2wibtqwtb.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2hhdyxuec.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2fgsfyfxc.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gt2nguzdyft.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzcaxyij.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2iowtqqsw.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kddystxo.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2qxyzrzvg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebjmmrki.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2lffqcfpi.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2upezqvwe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gt2tjkshram.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gt2roqgrteb.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gt2xjrpwxsn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vrkqkjpc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2qchoybur.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2uznqsxnz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2waqeewem.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gt2btdxomal.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucpgdxxp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2tstruzbs.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgavumg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gt2khdsupqd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odwhrnvg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gt2rvnaynpg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gt2qduisovn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2yzkmacvb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gt2vuryhrej.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gt2kyakogwg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2tyioaslg.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gt2xoeqwmnh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ttilhnag.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2jvbhdkpl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvnhucsd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2agjfsybz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gt2bvrxsveb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2uqzfefdu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gt2zlvelwzi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wvumoydo.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gt2ycllndci.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2bottewys.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gt2kqrqzehj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2jrtelqcs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2tvvsictd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gt2lknfqlhn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gt2nypezdjj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2boplmmvg.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gt2ggpwdsqa.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gt2stynkeow.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gt2cyknoczy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gt2ilfyulqj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhewvjmx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2vtegsmki.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2utcipils.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2zuiztqug.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2vsrjipei.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2adhsadhw.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gt2rfavdtnr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gt2nfrwajnm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gt2ktczcaoo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2rbwbixrs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2akvchmuo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2sfpcpqnj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2zyhtjteg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztrgnaaq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2syqxvwbx.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gt2qvuxznvj.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gt2blalucij.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2lzkrpxtk.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2cwbvqraf.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2oqctrgli.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2yenkpdwd.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2pzmtqivl.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxlswguo.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gt2arjbbfto.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2svroaqxm.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2vortlsuu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gt2cdrenmpg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gt2xfipniui.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gt2ydguyevj.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2hemlwbjk.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gt2jkznobdl.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gt2ejmezber.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gt2sfpbkvay.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gt2cwrskweu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gt2bqfztsyc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2umniivdq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2zwjnpbvx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2tpkkdymk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2lkkdgxab.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gt2iwffvksk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2tlmmnbha.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2yrtriixy.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2dnakhblm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2lilcgqdq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2tpxbncqk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2xoqlarha.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2lgknidrk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2muudwdcj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hoqmvofa.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2turymsgf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2bdtvkjsc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2eqtftnwb.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gt2gofkonrd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2znaeodhf.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlggxjem.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gt2zupgdsrm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2hvevibco.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gt2uzxunhvh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcdnkgob.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqmuftsx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gt2xkmfbcea.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2nvswgyns.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihplaygh.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcggsecq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gt2qebzlbfh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xiaagsbv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2jfhcvjro.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2sejmducl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2rhuagcsy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gt2shleeiwo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gt2izpuppvr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gt2cwnizcog.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gt2qncixszu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2afggzocc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdkatkbn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2qxqqsobo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2hqgvyako.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2bzwbhhzp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gt2dpymvtqu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2ztbkyvlv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2ogoflelm.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gt2keevtfkb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2xikafzmq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gt2ruwywjhw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2ccpmcbnn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2kieintcp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2kmzriuvc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2drszizbb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2xecexsfk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2eijzrtic.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2uzvifcru.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2tbwoqiwd.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2bjuohgfc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2cpvwqqsb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2csheeshx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaecctr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gt2mcvjdrmw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ghipbiwi.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2mgzkjckd.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2ogolkvtf.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2vrewmbhl.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2pdeufqpk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2envnzyle.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ljahpdla.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2hbwylkcx.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2gqengzrq.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2agljacrx.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhqyjudx.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gt2uktoectr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gt2mmubhayi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzruamrv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2mldlbmyk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2kanysynr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2kmeqoxcm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2dbzxdqyr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvztofsl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gt2azfuimgt.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gt2zdgdesmp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2ryejqpvn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2yauzlgwy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2fjehafwd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2mdcdwfti.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2zqguqwwe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2qlhinecm.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2nwzapuhw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gt2hqzxsrqi.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2jjqxmfpb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekmtptki.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2gjardrsh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2lkhcxyxf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2clywvijc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2ardoitim.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gt2oliniimq.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2pmooyxcv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gt2arqrjycg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gt2nnaagxpo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2znbknlzp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2ymkozawd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2zgzvgovf.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ucdvanqn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gt2xgevwgoh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2pnocuzjt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2vlvrjgjc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2fbiaikaq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owxdtsgh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2odpwdmge.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2vamzjiub.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fldvxaxw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2oyqaelqe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2ladiomis.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqqigqwc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dnuzldzo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gt2qlboetcs.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjtkcyji.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gt2ryodpeeq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2hvjsrrua.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2kvpkyjcp.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gt2ffdvwvax.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gt2lkjumtdh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gt2scyvnnpg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2ybwxhxdx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2xeleripn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2yhymtbrs.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2yczvqojw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qlsmowrw.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gt2lmqhucti.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gt2oozxuqxl.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gt2mtbvokrw.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2giuwkfps.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gt2iehtvuid.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2drgkigit.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gt2zxgqacdv.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2oigpmzfv.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2lkneobir.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2bjofiotp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2uqueruej.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gt2lwgdmdoy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2urdvuqjd.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gt2zalrtupe.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2apmsadkd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2fxhaccqj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2kjftzneh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2etftogrm.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gt2zogjxcbt.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2ugprhcas.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2ordthvtr.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmlwsyit.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gt2iysemhuo.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gt2szzmluig.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyhhhggg.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2hxsyzkqn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2vrpicjcr.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gt2jgawmimj.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2qmahamwb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ozoolrzh.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bxlrtoxu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otarhbur.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbevecrz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2cpozaxww.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2tkixlxor.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2srbffwly.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gt2ajntkccb.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2nllpqbfy.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2mhzckaoy.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2txqqvahb.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2gbeybtpr.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2hmleugpu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2gnksgoon.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhjceyey.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gt2mtfpkbgf.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnlyyrbe.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gt2tgjuxbip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2zgdmcktn.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yednfdix.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddaixofq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2acotyqqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2xpzueamk.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gt2bojhazte.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2jknfpwlq.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gt2bcxzxpzu.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gt2mltyrswj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yoixaznm.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2bxocdqzg.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2paxwjzsv.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2ozjecxib.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gt2lfqhksij.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2txlzxued.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2jxcsuafw.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gt2uuadfgrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gt2tmanexkn.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2ynjzzteu.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2xqusvtin.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2dceunvsc.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2wshfuolt.html


<!-- 参考信息 -->