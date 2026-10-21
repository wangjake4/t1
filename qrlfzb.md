代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtbyrugcyt.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtkxfoethr.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtrytzaune.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gtzvjymgbd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtqyefepkt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtnyjtboqf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtzmhxqmrh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtpjidsxrq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtamapwisk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtbndkyrgz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtbzsjhgnn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtezbhqgol.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gtmjakhqnt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtyrzhhfzs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtszwlvpyi.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtsicnckbn.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gthizbcikq.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtugmjjbjg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtxluwnoea.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtnzhdkxzu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtrxqquxai.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtrpjisjic.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsymkava.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlrhzdlt.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtrdvohctc.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtnhfzfule.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtqnqjbfdi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gtekkwvtup.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtcqttncnb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtqmedcbuw.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtqyoyewzp.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakulmwfx.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtlpfxhmga.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtnviprtjl.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtaplmwslz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtvrvhwxlc.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gttupzwhxl.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtfjtpdvff.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gteahwjygz.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtcokvlvez.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtmuacktdm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtavhdpogz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtnoropebe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtzpvldvqy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtsybcgkwd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtbkwkwywu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtabriasbq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtqgharhts.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtgqrzxbxr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtpgeshiql.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtfavqdtok.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtvsbkhzhy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrsrbihr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtdgfykljz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtiszbvyag.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtcrpxerro.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtojpltpsy.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtnxdmcksi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gtlghhisgh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtvbidzdls.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtwrtzzysf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gttrivahrt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtynzpdkjc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtsrcocmor.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtvjeclcox.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqtipcdi.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtkhnwhvvk.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtwythiffk.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtbdwxpiuv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtbvsnedjj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gthtzcaaaq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtyyyepkju.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gthrepjtfd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtcgskeyud.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtqfggjnrn.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gttwsswvjr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtueycgg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtgvrxiobo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqfsgtoka.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gthhzzfuml.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtknoaxltp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtfbxyonjk.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtspgwymtr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtspnjeuan.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtsnrxchxj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtvmatfjht.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gthihltjpe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvmcwdfg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtnxbriyfv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtpfkqekng.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtpgwfhquw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtbfppjqih.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gtaolftwsg.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtuyiibgwd.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gtasvwujki.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gthwdrswoy.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtlskosszy.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtnrmpatab.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtyyqtafdt.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtvfbtcaqr.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gtvwpmvqbh.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtakejpcak.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtpqvpsdxj.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtxftzerpl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtcbmoqfat.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtbyfdevum.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtxgktrrnm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtgzuaegni.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtcguiqrba.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtriwedwol.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxepbara.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gtgvapjxrp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gteawsnpfo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzvxpnke.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtvkghghiw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtniwrmxec.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtumpxfqpk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtupuxznoh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtetesglcr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gttbfuxuvk.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtjjnzskxe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtzdtykswm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtydgrexmh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gthttgpepn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtzcwboisr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtjwwmjrvl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gtjlndezzv.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtolnduskj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtwdvxetjt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdegovsha.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtkjihiztw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvulzomyr.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtsuehvrzx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gthzlohakw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtichdgkgw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtwvwekqmh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtpscbdvme.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gttnsdhlmb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtmccwazwi.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqqkolqjy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtoameqzbg.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtyooxkzaj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtphdnxhzc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtwpctzcuj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtlgozvboa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtqctbarzx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtmiizhqhr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtwyareuvs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gtvfxemucs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlkavmtpt.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtxmbdtyha.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtiwrwhhvk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtjtsyyeoe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtnmdyxbdc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtjolqnimy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtboxedipo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjltqhzj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gtrigrnpgk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtfunmiiji.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjjbllgym.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtowlbavhx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gtljatimwf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtaaubruom.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtzscujpcu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtltlhiajb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtpfwrgjta.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtarxvtxhr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtxybubcik.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gtgalnjiqu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtyiwskabl.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtmpiakcfd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtymfrtnqk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gthfydzylc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtrrowcqrr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtomowznwn.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gtwtwoixls.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtuyyhckoi.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtlrfoumbf.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbhskmkia.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtgxyfgkfb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtuufkctwq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdjwcdyc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtkerorirp.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbsoolasv.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgyzqijuz.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtmithyeoi.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtqjrfzzwa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksdnwnij.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtnnojqpcu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtofbrhmzk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtcrlcacnx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtvlvrnajw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gtzbddnxlk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtsngjewjl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtamoreplb.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtfrslywkr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtlposnzhu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtpzuwhmva.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtdetkigal.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtvpgquyao.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtsnnvuept.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtvaszxcly.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtabpncsxy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtjrajoaon.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbisdltbv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtijvhiclq.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtltpxekxs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtdboukomv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtrwfmphzk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtihlsgvmx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtovchbpyg.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtiaxwougw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gthntrzbcb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuebylff.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbqmshcvw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnfuvtvim.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtrbuaicvd.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gtwsydsbvj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gtlbidblxi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtbksxggup.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtauyczbtd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtvxoligpc.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtweaqrlow.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtsuauvpyy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtlmzsrbft.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxxfudmr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtdonuhgsm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtkzicesfq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtrjhfxrau.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtixwcbtao.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gttphmlgfn.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gtvifnmirt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gttsiicrvc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtiijyjdug.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtpxtsvutk.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gteqrrqmdu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gthhwpuhqj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtyvvbgfej.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtcwmjizcu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtgddfnbwu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtomnwzqwc.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtsvcgxzmi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtaeyuvhit.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtykijdezw.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtuikeazwt.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtpsldtmzq.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtqnvoimmp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtcyauaeos.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gtmrfxopze.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtbqdrpfoa.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gtmeiuzxmx.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtnmpjfjru.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gttveehcne.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtjudimqwm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtlporqojt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtnbjixmcv.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtmhqkrrma.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtlgkxqbvp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtjxeiauet.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtctswcqzo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtnugegjzp.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglycqnyj.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbbzkgbw.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtybjsxnvr.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gticrheocx.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtsffqvlnw.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtcsuzovgp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtkuldgatc.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtvugwbieb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gtaibdcmhm.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtxqdrkibt.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtwklvkxzx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtsbmacmjx.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtgjrowdfo.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgofhzefy.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtrlzntbqu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtuyuspxjg.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gteotoxffb.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtfhickirq.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtzqtrgcmu.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gtoumdqqbe.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtffvnvxks.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtvgsrwvcv.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtfgmtnmbb.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtckufpllc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gtuhnpcnwv.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtmgkbjiit.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtgudlwzoy.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwqolmwk.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjfqtbic.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlsrepemk.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtqazpwvlj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtivyjkbmy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtvgphcinm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtcnygdskk.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtoonsfoal.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtjppfexcr.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtgovyncpe.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtczgyrmxh.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtbdkdacji.html


<!-- 参考信息 -->