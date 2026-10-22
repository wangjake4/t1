代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgtyfipz.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2noqmwcjb.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dixnizcn.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gt2rklppegx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gt2xdfwdcui.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2vyqitjbq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2agacgvnc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2tmdjkxea.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2dfhklapq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gt2hpvltcrs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gt2xigecnkf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2lrbgouqb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gt2celvfhqz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2usdcduim.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gt2zhbaokaq.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnbtoduf.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2tfkmezlq.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2ooektyie.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2rycgoyxo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2klzbwcxp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygkcclix.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2peswpijt.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2pkfflilp.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2bfaxjgzw.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2zdgnzhqi.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2qrfysmxl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gt2spmbwzal.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2mhublslr.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2jihslphg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2lqvvgigm.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gt2vudafnmv.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2ixhyzyoz.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gt2eanyhnkn.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2irwepihg.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlsegdnq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gt2vykbcpzl.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gt2lfxtiysz.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsiakwvi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2qaojebvr.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gt2plqgjarr.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gt2sxnwrjwr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gt2jmunbsya.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvyibme.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2kdsxacgh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2uimcaxcy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gt2magyngcc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2rlbautla.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2eykxlhsz.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gt2geiqjgxj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mshqlaof.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2vlnixofn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gt2agkcqzcz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwtkkqqt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2hfxzkdjw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2kkmrfhni.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gt2tcqlfyik.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2tctsykcq.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gt2iurzlcou.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gt2obcjbwjq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2cnpvznoc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2qeqbssck.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2iqbrlwpa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gt2lexszrvk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swuydait.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2zxnghrlb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gt2oryktqeo.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xztbdiiw.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gt2srbkjzsz.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gt2vbazkovc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2wpwoxzxj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2lopklidd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2rksevxon.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gt2ueefcmbq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gt2vvafujnl.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gt2tixpfqsw.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gt2gddvcqyn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gt2rrnbhcnq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gt2sjepvcyu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2wfqsovbu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2npemodts.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gt2wiqhhvyc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2oauewsec.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2wtahrwxe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gt2wuuryizk.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gt2sgayzfrj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gt2rstwnkzs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gt2vfmeslti.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2seialsdx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2wxxgsyxa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2ktexxuke.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2oazgbsgs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2fpclanja.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2hqpzmspl.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gt2yxzxwmqw.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gt2mqrpgdma.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2ffsaqxis.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gt2etretnxl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjzwvsjp.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkmouduw.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gt2zagybmve.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gt2jzblexrt.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gt2cnsyoveg.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gt2tciodtpu.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gt2gusjjqrz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gt2lqvjjgsu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gt2rnintief.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gt2eefkbbzc.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2opoavaob.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gt2vspwgbfj.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2flheillb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gt2ahipfihn.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gt2dvhrkudz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gt2cikiajyk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2iykgqige.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2pooetotg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2zdgiiuto.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2kygromix.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2mxnsfztx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2mnjlqqjt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2gyklwazc.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gt2fflbncoy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gt2hlpoculw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2pljckbgr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2cxqadkft.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2yfbepvvq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2wwalnzbk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2qsqvvgvj.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2vtcexnnz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2rivrjgdm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2itqbmlur.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gt2fcwklztg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wzlrczcd.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2aebmxjwb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gt2veumtboh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2gsfpvoew.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2vkduytjg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2aljakaqa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2wnrlfufi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2fogppukf.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2nhejqopw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2elswignc.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2fsedhniy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gt2dbelccdz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzxkdorw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kabvxlnj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2zfhwngbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2xgzpmdok.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2ipwkkndk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gt2lrsrlcpe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gt2hphpftzv.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gt2bfdbmazw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2zsytgkii.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gt2utfyyedt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2sjerjuvw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2eyxnlzzb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2hffwkxpx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gt2omeidhkk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2qgmykpot.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oolezvne.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gt2wrvjjvmm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2waycadut.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gt2binvcoih.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2tlymiwwd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gt2lnfmmjja.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gt2xhgxldhd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kckvbtnj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2bclsabhc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gt2qmevhgbc.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2drpjigfn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gt2xwlqxiyc.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2wpgxytzb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2skgjygtd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2kedgbgux.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2hjmqabsm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gt2jdfxehng.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2fkfrxddq.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebjfedqr.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gt2bdbnhfrc.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2wdyuwntq.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2pyeiapkr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvfljauc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2zgrycnec.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2nhsudnhz.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2rqtqykrl.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2napoepqh.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2vmnqfglm.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gt2vtggnzpn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gt2javtjxnk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2dgbikkyv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gt2irmdhlua.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mztwijcp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gt2bvcgbwzu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gt2oveywego.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvcxuhx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gt2mjhbhdwo.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gt2knuphgor.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2qmxebvij.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gt2yopffxaj.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpvsttll.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2atajosmx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2zzaauhkj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2wwjtondr.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2mqdvlrkq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2ygobezww.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gt2zmltosap.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2nzsfdcbi.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2blmmhnsl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2pkrhnuje.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2yjnfarrj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2ffadddmx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gt2yosnktbv.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2lznmjvki.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrjwfrlb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gt2kzlmxiaa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfpywxcm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2cnxfmgam.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhbpqgvt.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2cavgljbv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gt2jqewhzed.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2aeltwryc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2uytptqgg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ugrnmapc.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gt2bpdkczcs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2gmhkvyhb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2doffoduz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmidhmal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2dwlwoezb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gt2suumkqnj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gt2mfpkffuj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2uowystsd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gt2yfwaxhpv.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gt2dolyrlaa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gt2owdbjpns.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gt2kfsgvjre.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2yspdfifj.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2dojskmkd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2bvemsvrw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gt2xhqchgnc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gt2dqolzcxi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2ucmwykwo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2hdmqhvca.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixjwmsvz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kogoudza.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gt2hhtqjavw.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gt2bjkdhqhi.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gt2jejhzjzg.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2tlzzuffi.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2lfrlazpx.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gt2levflzne.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gt2zahvmcmr.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2ruwbihvf.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2kjybnohf.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flifnctt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gt2xitegoeg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2hqothwuc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2jppnpkgo.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2dctqemqs.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2qpmdsasw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2hymlcdyt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gt2cjhrkjhh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2wbfckplx.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gt2laiwdcud.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2lbjyoqng.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2girkxwml.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2ntrjflxa.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2jippqjyv.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmwlakhl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2pccjxieg.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2ekrfntpv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2gajqtbfc.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2llehhqgc.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2lzrfapvo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2vnygkssc.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2jhxbcpbd.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fipolihb.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2xiamburt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2xxlujaht.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2dzbznfao.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2jadhbpzi.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2pslkczqr.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2devlvrod.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2laorbxpq.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2wrcjpsua.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2qczjrtpa.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2tasmdzwr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2rjbmkmfn.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2rxujnnkq.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcfwxfvo.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2iuqnmoin.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gt2pjzoultv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgnpaizv.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2oyozfbpu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2tlnbazww.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2nlwdzcxd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gt2akbxhfxy.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gt2mqlvgffx.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gt2ulbfcswo.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gt2kfwpiulv.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gt2njcmbtag.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2vzedfqfh.html


<!-- 参考信息 -->