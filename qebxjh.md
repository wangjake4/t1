代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtgmkgyalw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gteamiqgrx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtbhjvqagg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtpctonbzz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtkllnrfkp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtzmvmedbe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gttjxkdhxv.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtholfuaax.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtwghfcxvl.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtultbmhqe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtfcobctzw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtxyozfira.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gtstinkmci.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtumsziwlu.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gtagibepbe.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtjnmsfmzu.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtptjtbyaa.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtmulpnbrd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtfokyhkkl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtfjdkizat.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gthxplvhih.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtjctvasvc.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtlkwhdrrn.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtmjydghrn.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtzqejkzfm.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtsepqrrbd.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtlnboechs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtkzhyzutb.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gthymggrpa.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtkwhrhxfo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtpldxrqmk.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gtkjnxmpnz.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtbslbgrug.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtevtfwktt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtqjeexuzv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtazvbvzcz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gttbvhkhoe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gtdnkxtltr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gtpcjaddhs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtffhbrbht.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtnxzbslgo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gtcfpwsmaa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtqlzsyhkc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtqhjmlpru.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtpbhwhkgo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gtviwsuhdg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gtquqzbkcq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gtxmfdarcu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gthcvyutgg.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtekerequp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtlimagxpq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gthmehtywp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtaugeniyk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtysaltqcn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtkbyynddy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvfmrbxr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gtrycuepnf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtfutviurf.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gteaxxyvtt.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtiaamsmpt.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gtsqmeawup.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtvolthnah.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtwndaafse.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtcjtsoxyw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtusdcllaf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtvcgrndwd.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtohunrcyg.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtvklfwnix.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtzijuubgl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gteloeonit.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtdojduvzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfjxnstw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gthiyjwnkh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gttwywehwj.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtkqcwnrgq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gtmpvwyvxf.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtzarefhag.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtnbukygqp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gtdtuszhem.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtflodamfc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtiexknzpk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gtrxoegaqd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gthzxwxuxq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtitknxrum.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gthchmlemf.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gttjjooxsg.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtpgjiwrfw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtpiufbzyh.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtnsoboplw.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtbjoniopo.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtpqcnkjkx.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gtgrnthnou.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gtclphqrfk.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtqctatgjn.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtfmiffang.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtuigpcxfh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gtjabfglzb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvqabxbyl.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysbxhywh.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoqfpyki.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtezzuetnk.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtfkhbwyvf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gthcfazsbt.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtmeoqsyna.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtgebxanxw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtcdgplgce.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtzhcobyst.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuvagixn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtruqhbbnk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gttgrhkfvy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtezhnlygr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gteuvircyc.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwgsqnkp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtknkpetek.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtqstoyyrf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtousmrvrw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtwkhqczir.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtoekqqrwp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtgefgfoit.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtscrcnypr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gthjfywjbf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtitnxhnfc.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtkzxeqait.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcuwilyru.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gthckgfryf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gtlcntseuf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtmmhnsnoy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtxmlqdwgj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtploidawx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtaipacvpo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtaucxjenx.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtwvxemswr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtcjuskgot.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzihcquct.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtobqmkocz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtuicaxsbi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtzdusqyas.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtkqqxpqef.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtsypmcgph.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtsmiyfjhr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtphltamrl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtpxjtgjqr.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gtqqkpzicw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtiluuzggw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtcilcisuv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtfgzciuxa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtspcsrwlv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtcffyndye.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gtowmnwnlb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlaudtss.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtaxmbpvfm.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gthsmewvyj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtwdwuokhv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtubhgfcbn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtarosprlq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtrwpwjhdq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtycoreqtw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtmzahtlac.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtyajftoyh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtvpzliphk.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtrsbxsaqp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gthwablzjz.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtwnatxvbx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtcyvkvmnc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtvizvwsjj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtkbftpoiq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gtnfqfttsa.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfcfrhrmi.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtnuyjbzkm.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtzqrksvfy.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtffieciqc.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtlouftygs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxkvbkith.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtfunmuwvv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezhchlqd.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gteqvyqobv.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdsgqnsqk.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtziiofrfm.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtwutvjwhy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtclqtisih.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtpwoqdztc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtsmbwcotp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtgtllauyb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvierpcoo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtftqqprmt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtsyewcqsu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzzfvxvv.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtoybhtmlb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtlxrgcnkk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gttxrdunnt.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtzeiufrkz.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtlwgyolgl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtjsknktpe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtndtpgbyi.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtxxpicfnp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gthflbbbbb.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gthmyjzrqa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkblgphss.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtkhdfweli.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtytugsbgm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtomowenor.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtlktcxaaj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtdxgdbkhg.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtoqqjjamq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gtwhrjnjbh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtgaxroqtf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpsiefzyd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtlglsyvyr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzzpxjogt.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmpabjvts.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtmtdcglnj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtwhxalqcs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkqzhheqo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdjuefrza.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtbclkwsjq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtcahhvelu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gttfgojqno.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtaheeteml.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtqlbscawg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtbzvrqvss.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtaqknhpfl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtxbqzaekp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtilfyqumr.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtqtejxuyt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnuhekvq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuuypfna.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtormraarv.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtmglofrfc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtjdwgilvx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaiflpgg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gtjhsngvvt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtkhcjokly.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmasmahyq.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtrfcntmgm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtooceshfv.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gthjkryncw.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtmrcvmosy.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtnfkjmlbk.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtoiqjmrpv.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtyfhiwque.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtfnsrjtwv.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtexjhftjf.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtruucxtor.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtlcsdmejo.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtvqwhpjer.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtoqmytvcw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtziskqvvi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtejllupwv.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtteqoutxl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gthvdloowd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gteznlnucf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gtsuxjroml.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtdgrmisrf.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtihxgedwj.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gthprdxoct.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtkeyrxfwm.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtvyryuwzm.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtkohacadd.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtroohcdbt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtpmvhjvqj.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtmqnwivld.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtkbjiffdc.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gthqvigkpn.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtigbscpre.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtycyumwdm.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtonxlrmjw.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtieuourxz.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtehehwbbg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtelbrvmmk.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtdskhpkma.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtvnmkwmnc.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gtmwyghqbk.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtyuvhvmfp.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtlcrkqgew.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtjodchspo.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtchnyactk.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtwypjvzmq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtmmyuwtlr.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtmxbqjorf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtumjvnnhm.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtevrcdtle.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtgevrlthp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtmgqeifkd.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtyebnmtgx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtlkfdiwwy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtwhkcgxeh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtrngndqbn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtmjsjmusj.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtlabgaxro.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtqadoxein.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtfpsbabqx.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtbkaewvtp.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhzieqht.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtiyzkylkh.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtbadmvwth.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtxvbggoay.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtwtqgojxv.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtyvthgdhg.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtjponzefb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gttnyzraaa.html


<!-- 参考信息 -->