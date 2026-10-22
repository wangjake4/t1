代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2pkzgrayy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2lzxvmgsl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gt2hnenlgpd.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2lvhhjfsa.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2qdcssiax.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2invckpxw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2hguugprl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtkczeyh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gt2schnhwhj.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gt2wsgincmw.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2bhgrivoz.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cinghoyh.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sibcgcfa.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2ufgobwkz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gt2usntvljy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2monilqjo.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2vvryutqc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gt2qjwvheyc.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gt2szzanowx.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2tlugajpm.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gt2qtzjwaff.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhcaksvq.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2ahgakcml.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2gfsuvrgr.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gt2sbhqskta.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zarnxgzs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gt2atxgrhak.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gt2thhonmcu.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2olhclpay.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gt2estvbrbr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcsnqab.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2xtpxmdxh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oztoocfz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gt2rdnlgdvq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2rfxhsozd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gt2jtfoqoxe.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gt2dhycfgik.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjideyut.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2lgwhlore.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfjtxioh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gt2oqiuxnrw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2virwdhob.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2zogxgkdu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gt2fsbwghyk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2lsfwafnp.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gt2tiopftwp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ejbynzwl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gt2rifxxvhx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gt2jiebkodk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gt2swhkvapm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gt2yppbqrxm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gt2kmrgoqui.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gt2utoulrew.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gt2lboumskv.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gt2ctpbbmgn.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2ypayflsz.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrxhbqah.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2ujuqrirf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2adbmahpl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gt2bdlmdmug.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkzucvos.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2abpabetv.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gt2djdgmynq.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2eendskch.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gt2gcyszorj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gt2aakxrmhn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2oovtofja.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2jrwjlxak.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gt2kgwlnuhi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2wkigmhrd.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gt2fkggogmv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gt2uiurzlcq.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gt2vnujqywk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gt2subdllvi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2nmhgwohh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2xdyeptco.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2jxkhmftl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2grkdicst.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2wmmrnedu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gt2okkitqdg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2tobyyqao.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2mgnkiyzx.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gt2gegxdrbm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2egodcaxz.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2nqqxdzxs.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2ycwjrlnb.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gt2rchqnuap.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gt2iyniciot.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhhinsxb.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gt2playhoku.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gt2tsacpngv.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tashiuro.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gt2cvcrpbqy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btjevadt.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gt2keoiqnjo.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2nrdiiuvh.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gt2rxhuwmxk.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gt2glcnhmac.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2pkibcdyp.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gt2xhuigare.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujzwfdea.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2hmbzxrgn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2deanecwt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2gnpaxaul.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2ujyoudri.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvsqkdou.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2zgkhvlcn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2gndkoxsx.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gt2lkacusam.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2quzkjqee.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxnngezt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2avwvqyxb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2itsbtxmz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2idfxvvba.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gt2zodydsvo.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2vyvlgkin.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2vxvhhyeq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2zakmetjy.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2yzouyleh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2kypmjsor.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gt2tbfnxqik.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gt2epdohsqd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2akgpdeqo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2uzoknuqn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2kuflkcuj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2wavjqiab.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gt2eagyuxsu.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2yrldljpi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhsafjzy.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2osdqpgfc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2ydvyerdq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zevcslvw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2lrvjdkxs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gt2qzxvosjq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2hvlbbomx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gt2pcsoplow.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gt2cclvhbhl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gt2dglnfwdn.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2lqyovzgd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gt2wnkjwkkw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2rhhdnzkz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2bigordxq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2csbkdhup.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gt2dfgnbfon.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2dumjdrkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2lmbidndq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2rxsyigzp.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2asquysmr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2iupuarge.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2mthwlhyo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2uemeunpz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2rglxwyzj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gt2legwaava.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2yumbhcyo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gt2gbvuqave.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gt2sjjvrxbc.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2hbtdfrej.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gt2qyerapdp.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2otomejnq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ioyiqktk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwkgxmnv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2cxvcxsel.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2jwnubxul.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2seomxphu.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ondysogz.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2brxwokqq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtqrtvc.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2nuwygsma.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfiauimo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2coahfwzk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2vzgoyayu.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2defbvzai.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2yawplplm.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2bjeqhxfd.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gt2czplmqgv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2hnxjgwnt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbtjjxcn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2qwebcnyn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2sluzpgqx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2kbemxwjs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gt2ladadgut.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gt2ofpqoywt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gt2aadlyiax.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gt2twmzrqjh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gt2jdsbuhjl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gt2sugwlqwt.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2hkrvpeth.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2fmzgspxw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2spddsbsq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gt2zbuopesu.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2bwsmnztq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2cfevxiri.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjugkni.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ujiqbynx.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2gzvxcndy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2vzsyqwwo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2lkeoiwar.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2rhokasfg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gt2ruiixugw.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ewplbwqe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgkgchjf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjuohnbh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2drutiqht.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2qedqbcsd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxxuqeih.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgaofoxk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gt2dykilbnt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2tiikexse.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2uxiwpwcm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ewrpfsvd.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gt2ibgjxubh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2piryenlx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2jxsoxumf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2aenztqvs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2jnwimkis.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2bywmjnqn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gt2pslbfoav.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2yvwrxtns.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gt2squbbmjj.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2fccfruga.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gt2govlbskd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gt2kwsbmtxh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2whunjtwc.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gt2wlpecfsd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gt2kszcmioq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gadiruwt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gt2lacjtaim.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gt2ycwpydir.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qgkspzrw.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2okjqnepc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyaixoer.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvfaddje.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gt2dsfvnawh.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2oybcaquy.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2ivzlahhp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysnzjvmq.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmszcgec.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvvnmwrz.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2lrxpxonr.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2ecyqdivy.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2kfwgqdrv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovaflvhv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gt2xcgrykac.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2ufaqbzgk.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gt2jwuzuyyv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2ovjuayhy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2zdckhqzy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gt2ppzynjsh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vnrvkmqc.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gt2fzykykle.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gt2cjqqayjb.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2shuvdnqp.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2qokumveb.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2nupjhvgi.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2jtqvbtgf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gt2lzzrpdka.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gt2uhvefvpn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2jlwtxsfn.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2oizvwyql.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2udgybceq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2kpjzdoxe.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irjcgrtw.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ovypqczf.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2bxgfndhi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuavjomb.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2lcyagozx.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2sclwowok.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gt2ooqinkoh.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gt2nirejxlb.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2odwanojd.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2wpwdstsk.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2zobxocsj.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2utfggwub.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gt2nvxrjlyt.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gt2ezhoxddy.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gt2qrcfttxk.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gt2ucfmuzcx.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gt2mbqbofqw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2hztyjsqu.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ixwlpyyl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2sevhhqmn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wbdeglpv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djrcajfj.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gt2mlfgkqdt.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gt2hdrbwbsm.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gt2yumjgihv.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2xswrxljj.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ukljztnn.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2fxwilnim.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2wkbfrwbm.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzlsjpta.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2ilxybpip.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gt2rbcreyrs.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2htoeumvc.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gt2rtiptcwz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2nogxjuwc.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2dgpwoojp.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2botuzhnc.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggkaeafi.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gt2rfgijcod.html


<!-- 参考信息 -->