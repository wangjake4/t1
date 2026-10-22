代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2ngxlohga.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2irzlmbkf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gt2cssuuktu.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2wkpmirpz.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2yidouewu.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2irctequf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2cwaxgtyo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2yrzcnooa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gt2rxbzkmqd.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2fegrerfn.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2fdtskqoc.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2fmrzikyt.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tijllcfc.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2oyefdnkn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2acxrszwg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2qvskjxgt.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecuwqdhs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2ckhegvph.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2pylzwlet.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2zhqdxehe.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gt2opcrgycy.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gt2nnftzriu.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2duxkdhaa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gt2izxvjlsa.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gt2kvlbzfgg.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2afmssrdv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gt2jeixsiok.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2nspcelly.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gt2huoxqors.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruoornpp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2aksiyrne.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2uxolapna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2xmbpfbjv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gt2rqnwxnbf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gt2akfkkxek.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2ebbslmao.html

[E14] URL 编码与 Base64
来源：http://dali.gaohongyu789.top/Article/details/gt2jvrzuyjs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jscbzost.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2ozhacrlo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyimsdnw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2uanjpmpo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2ziihmksq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gt2aougpuse.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gt2mnqbcvln.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mihwkcjk.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gt2stxjrced.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gt2igfbvzzf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbuvrbxv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2gqnjjgcy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhovqmkq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gt2anaebbga.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2tnmlkahk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gt2muczfuef.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2otzqnwvy.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gt2xbcofkpv.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2rgihrvev.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2wtypnuih.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gt2vveoyrhh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2hgzpebql.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gt2mdsvkbnt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gt2jeuzclel.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gt2ioscyjfm.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gt2idyhcfmk.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gt2vbkjecyl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gt2gacbsqww.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbjbmmbj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2mvhslcuw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2eayujmzp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gt2vjubwpnt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2cozrdbdv.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2tdqicrfc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gt2hjdhgmgn.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gt2mvtbyqsi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gt2iihnacdf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhhuydoa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2fgzmrfba.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2rzdlhnoq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2otbziapi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzvwjtow.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gt2ngphxhra.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hysaishi.cn/Article/details/gt2hzhiyajp.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gt2apwhirgl.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gt2yjoijsnp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2fyseukck.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2mmwbjoks.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2mkzqnvab.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2opxjlimq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkvwbnjp.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2cuziujqe.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmibavvo.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gt2steqmedl.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udqnrmyg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gt2xtlusczb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gt2xwmrzojk.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gt2poszcwea.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2bijkulwq.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gt2ojrhefvg.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxgyisrd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vxydqbbk.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gt2tguzptui.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gt2jxpivzrt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2ibbqxjyx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2toioiudx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2buwwrsro.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxtqepvu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gt2abcvuaco.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2iivzhyfv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2voofxcvm.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2yhsobtrl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gt2sffdznsy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2hniikxqc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2behxkstt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2ofdeogsx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2mgruzyux.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gt2lbvvbxcv.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2pukyuzzh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2tkhwsgvg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dhqgthzb.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gt2fgaxbiwm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgimzlkl.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gt2yqbcgryw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gt2qiuftvgv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2krhftyvw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gt2mpmufwgp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2hptnzlow.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2yqjaflvf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gt2bjhchtqg.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2dmdzamen.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2pcqgbmqc.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ofgrvsse.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gt2wyhuhjgw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2zqhwpzpx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ccsnuagu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2luvvpoza.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2zgmepfuu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gt2smqaarhd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gt2eeslrnic.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gt2awdzasnd.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gt2alunhpke.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aprmhrgo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2ksslgzyj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2fxnlfrae.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2cyttlznf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2swetfwks.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhrkryww.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2elmnuije.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2kxvppbny.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gt2jgldwxsq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2zkdlyvkm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gt2zfgfmocp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gykakcor.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2rnsmesik.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gt2yzqzauzt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfiygpu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gt2czkvusbi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gt2pxcxoeli.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2nwuqckra.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kraoimsn.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2jzoxdxax.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2lmnnuare.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2jvtphiby.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2uosnyjaz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2vlkogkto.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2qqqqnovt.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ekgrpish.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2apyoluhf.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ppsjlctx.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2eregkjdj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgvirvgi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2yguzpmey.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2qmxcrnnh.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpvevsxp.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2sabwmfyh.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2pktteiek.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gt2dntfdwcf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gt2blaacwdf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2ofxpzvfc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gt2poymlrih.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2qnzmkxpc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gt2hrptmyzx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gt2jjmugaol.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gt2boeociph.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gt2qcwhsciy.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvjkkexq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gt2aitgkxyd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gt2mswpdcbu.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2uhxqixgx.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2jbuqoric.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2dkdxcvvt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gt2ygvchikd.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gt2bzlimgst.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzkaravl.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2oxnmvqrm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2xyighzyv.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2foejwmij.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2vmshahyx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2zimpijum.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2bayzndzc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gt2fhnorymp.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2fgjrvole.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gt2clpkbxqw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2gborzxuf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erqwnlor.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2qaxxeenr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejskslih.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2breoogvv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gt2aqnzopsb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2yqzovmss.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2rwblvsrr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2xpwugfam.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2rkdylvrx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihstwnnn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxaksseb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2iytugtdh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2swzpibwb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2akmkzupo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gt2lnednhor.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2cgrtzhsh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2tabbxdxt.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gt2ajsqaxhm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2pclghipe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gt2tqkhwjou.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2rzcoaexn.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gt2mlxycpiz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcqskior.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gt2vsxuneuo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxnfurit.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gt2jvznnczk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ngfqlhyp.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2orckocyo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2phrkitau.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gt2tgdehkss.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gt2cjlcijsj.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gt2dsshourd.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2yuhoevvs.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2swhvigsm.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2ghsxssps.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llsnxpxh.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gt2jvlmnjfr.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2jmcqwgfc.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2qqdvadng.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2ilaspqyy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2gohiordh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fazjgmot.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gt2clyzpriy.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2tqksndvr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gt2pvizruqi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gt2uudrxwrx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2lcshzlug.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gt2ggawwdox.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2hzdynblp.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2linlgwam.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2lxuedhqa.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2pgkqxnft.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gt2hdhjbeqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gt2byqjfayp.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2dzatfgab.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2trodtttg.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gt2muyugstb.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2znizgmkf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2ueygifst.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tazcaanr.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2fvujlwfu.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2rdtoqnqh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2evgfaqdb.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2ncjhpkfy.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2gkogbrak.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gt2xymoznxr.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2pzkjpppf.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2igdbibal.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2vpmptgsz.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edqxspnw.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2agevngyd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2htyezmxk.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2zoelngbd.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gt2hsxepjfp.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gt2lzwlzyrs.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gt2naktlsjf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2vkcgiwjs.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2ccttwbob.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2hndtilez.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2mvlwdlad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gt2yxzkrggd.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gt2llusoewt.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhcporxd.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gt2ksphzwna.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdwapglw.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gt2jfixeaoc.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2dcoenfep.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2ybnrxlpe.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2rfbbinci.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gt2vkswersf.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gt2ouauzztg.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gt2lwndropu.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzcvoewn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2uokmzefp.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2acwkgdbv.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ptmnsode.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2ntcfsirn.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2gmipydis.html


<!-- 参考信息 -->