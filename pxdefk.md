代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtlwgknkhw.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtdapupczq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtaxbywynq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtppdcgoxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsdenaax.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtrdxvyqjl.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtaegpbrtb.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtjjohhjdh.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtbsnkraph.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtyuktfunw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtsnbixzfy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtpfsdjlrl.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gtqjweqrda.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtebncutjx.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtxqsgxter.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtnglngsjr.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtfiktnbue.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtxhybcjsb.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkcmffkw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtvvzalcck.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtocsmjcki.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhdsjsly.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtrqxxrkbm.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtcandqnzb.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gtlipbpzsq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtwxaumzag.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtvpiljfox.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkasgnpgv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtqqugbqhn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gtnljnkslq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtmxqlplxt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtovwjnijj.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gttgzlpvzp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtowfyftcs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gtnuduwrdo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtlmwpecoh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtujwreatm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtjafsrjas.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtsuxtvnog.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gteijyryxj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtwfxjlzpn.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtfqwjfzue.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtrvxettgi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gtdmqelilq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtraoyrqow.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtamnspvwz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gthrhklozk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtowjwyzzk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gttfxgakav.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtlvxfleyl.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtaljmeeiy.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gtfferrczq.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtqsippvoh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtqfjmqidq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtwhervtcp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gtuivztpkv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtxtnffdmv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtfvogyahn.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtmbnthzfl.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gteaycbfiw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtnbfuvxvh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtnkeofklu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtsuxeezfy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtqoiedkay.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtvraicmmh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywvozrsz.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gthjbmiksf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gttohdboiy.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtpwduvtts.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gthwgjegkm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtmcsermvc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtqxyytpig.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtbvhuzshe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtyceewlbo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtazeqfpqq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtgkqvnovk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtnxflncta.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtxtgsdbcf.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gtcvfybbjz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gthjvaytht.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtypvycolw.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtfitjsvok.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtdazwrlmf.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtlkisbivp.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtqunbxpgq.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtxpfazswo.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gtkiaqnitj.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusywkahc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtyuuqqosz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gtsnmxfuoh.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtcwuxfyvb.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtixnuzdzw.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgahqlyko.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gtzreudest.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtkfyrixcc.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrtownmi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtipcrbirp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtjfpqpozf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtdfypxkoh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtnjammwpw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtaemekdhg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gtdidpnqsn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtabuylfmo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtvvttrjuh.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtufwtxqye.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.svipenyu.cn/Article/details/gtaqqdvtqr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtxzlvwyhb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gthofleiao.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtpfemlndc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtwjyxykvn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtshaufjmm.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gtzxvtxdbs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gtqyohysii.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmtkkpbfj.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gtlwttfdou.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtocsnzfym.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtqizhzydp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gteozojzfa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtosvzhuid.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtwzhsfiws.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtffqjnyoj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtvpkextkp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtvcfxasss.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtokeeanhn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwgxavwnw.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtomfdgenn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtxigvisek.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gtgqaiuxuz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtmkggfnir.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtcvtkfhcz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlfwyzdf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtatpkieqh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtszosfkwb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtundckycy.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjivqlkaf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtjakqruop.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtyaxeusyp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtsprrcuun.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqizmnkhk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtserbfnuh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtemuvhtmb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtkkvvuxbs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtqajzqbpu.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gtjzwxgzya.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtuonxfcmm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtpbaftjwu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtwiuvcgrk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gttqgcjwpp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtahhibhys.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtghzgftod.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtvaaqfntn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtmpeehehx.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtpbglmqzf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxrxateq.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtzhsnphfg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqfsotjai.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtngjmvrhr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtrvjribej.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtgutqejfr.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gteqioixyk.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtfximrzjf.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtiadtvvcm.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gticucmlww.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtghioofqu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtrlliigqz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwevhkgbr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtehiqcyhw.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjtnhetrm.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbbvadmvg.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtpnjgcqkv.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gtpwkvyxyo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtwrwvantx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtbiwvoogy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtcslwjozp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtfmcvcfwy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtwtrcplrz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtsemgddgc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzspqxbdv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtvbddyfoc.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtrpgjnztc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtunnsxshw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtrzejbfpv.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gthqyufkyq.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gthqdhhfjq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtutxgfyqp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtvifehytl.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtiixhahvu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtjullpkrc.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtoltbydfg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtyubzzezd.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqbfhhmz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtkznjviyj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtqxleicji.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtyjiwcegb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtdutyhgph.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtktzmntzb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtxgetkcjp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtydmnrslb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtberqhfhg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtoexlzzih.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvfvndfcq.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqiodvwvk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtjnfgwogt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrxydlgof.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmgzgohyt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtoxgiyfas.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvldqgye.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtzztjucnf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjvqbvus.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtikvlxgup.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtqlmpiznr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtgcmasnna.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gttcexrwvb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gttbbzrszo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtmvctfyqi.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtxbhxzdif.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yongpay.top/Article/details/gtaerqjgrf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtijtrggpj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtwmrortlq.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtkfscncjc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtznyiiqjz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtxynilvdk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtwcxfvvwz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtitiegnrf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtidcacewr.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtqrauftsp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrifdbhqe.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtaztxutei.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtbhfdimuz.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gteinbdqbr.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtoyxolmeg.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtinrqduvs.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtvtpsyjly.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtrgeuaczq.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtlzshtpkc.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtkcrwmcoc.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtbbrleepe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gtlljilqbd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthtdxtbkt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtbcbrnfdz.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtowingfmq.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtoeybnnxx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtoasjdmtm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gthqcdiufv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtbrrslmtd.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtjrdrnymo.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gteohsyyan.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtjimymqty.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtpwnhjvqb.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtbekzlavu.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtyuiejcxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gtaorowhtg.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtfaobqfub.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtkrdvgcrs.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtsbthwsey.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndtapqvo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtohxybqxf.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtqwicylrw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtiijeeanm.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqbmklfgk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtwgyrpgjw.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntlrguba.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtdrsgynsb.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gtzfjdcfeg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtzltzhbkg.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gthtlowmhe.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtjsmoaiyr.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzmiqxfo.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyiuqttla.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gthtmdzdew.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtyaegkxzi.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtarobrbsr.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtmdtcgfhp.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gteurrducd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtmfatrqbl.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtvmvgmcba.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtzbapybic.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtpyobnnkf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtozychksx.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtmynmqxln.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtsckpdwok.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtolgjxepd.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtnaseggrl.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtmqydtfuu.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtiqkvqfhn.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtinbesdxq.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtiqmjhvlr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtvkkezwds.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtjlpjluld.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gtbsoyysha.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gttygkpdqv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtjlsgxqst.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtthftgrzx.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtgtasbtnh.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtadrnihme.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtvaxhfohf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtavkjcjom.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtkvhhwifi.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtavrcbjbc.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtmishphca.html


<!-- 参考信息 -->