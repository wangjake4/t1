代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtdjymbxrv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtfrsgturd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtjfyxfmqn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtmpjycmqp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gtnlglrlez.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtpoosugvi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtijichcvg.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtfzpuofil.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtahfkpjzk.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtvarzioip.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpazokdz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtmqxaridd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtfbuwmsdk.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtqnrskwze.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gthpqptihq.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtujxnzapy.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtpxmypnic.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtmtsrsnkr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gttbcxxsxl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtsxsvjsjl.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqrvfrcr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtnocaodvs.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtpsdbtqpb.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtamcpgrdi.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtxoryihba.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtccnuldea.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtbpbskulg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtasjqbaky.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtnejeigbg.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtucadeppn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtdxwerrjw.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtvqqcjmrc.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gtjwpsugcw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqhbvhtzq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtzlwzzzyg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtxkamhkog.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtijtolwaj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtickmohnw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtjnlhzqyg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gtspwyjiry.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtaqelaxiy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtcuyrzwwd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiolowil.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtjgkxqtwp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gthuelisaj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtgesxnzvn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtuizkdrov.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gttrdlclfh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gtlquxskqd.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtxaezypoe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gttiqclupc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtyvbqvztc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtyefcdlqy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtusradvib.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtdkaajayb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbrzvudub.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtjvdfubpf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gtijtfvcpu.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtpyzubdwq.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gthsdecvnu.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzrtqpub.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtiyyiwaqr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtxaxfpanz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtwwvylumt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gtxgknfwgv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtatdwbuoo.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gtzmsuqxql.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gtpgoqntpl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtujxmtgqh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtpzhijnzw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtpthpshrl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtcphvjfah.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtyqheayfj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtdxbmfwml.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtzbgwedds.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gtkuvneugd.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtfxhynjqu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gtwhyemddk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtpfchyopj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtjmuovbto.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtqttwbtro.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtmbzwmsux.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtvmgsgrxw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtwrtyzzvp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtdeoeublx.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gtubuhmvxg.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnjrddvn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtuxlaxsmx.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthgovprkt.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtntstfmnl.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtxznlkebq.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gthobeirhs.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtpqufcdpl.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gtzlnsxjnt.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtxtfplteg.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtpfilqtco.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtyrppuucr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtvkpmtoay.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtwbvnlrsq.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtsekjjlgx.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtcljnxihr.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtaopjfphg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gteuridkry.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtpjirbipv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtsggqqlvn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtlpazazoh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtgeysdfpy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtqxcxrhyb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gttkbxdhtg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gtxslklilp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtmwntwvom.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gthyzeemjg.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtqebkwlxf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtljdlwzyc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtibflntds.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtdjiqlpwd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtrciblets.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtyoftnjwh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtuylpnzgh.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtunfgpfza.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gthhabnmie.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtthzcifoa.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gtpyuctrls.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gticglbpxu.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtntoijdzt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtpzncuqaa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnwywvftp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtjuemmhvi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtllilmleq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtzjhapryg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtqlwcdyca.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtscrzgfxt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtdtvijcer.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtuxhwnapb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gtvksyhomx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtcrnrrrxw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttxzuwrni.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtxgmnuegm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gthnjbohyo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtmgluersg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtduzgjpgw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtwmwijnom.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtxxijxulg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtgidweotu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtqxlxkqwy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtqnlizkac.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtpybkmish.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtjxxzcdkw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gtaagktxrd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtdjnsvblz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtrqopbspn.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gturfwrqtq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gthhqxhkyz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtszqvtvpy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtiaeuplhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtzdslyuma.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtrtwrnifm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgffrqzph.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gttfijobbt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtyciztndi.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtmuerewfj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtykjeafqn.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtkibjxzym.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtszzoqiyx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtufdgwziq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtwblbrcjh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtjlbzysnc.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtexeabyfb.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtrckjaawf.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtndeazkhb.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixfjeawh.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtzxizrxxx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gthleuwcok.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtictorlzr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtmumkqizc.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtysjgkeud.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtliwfmtuh.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gthoprtvpb.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtywjfqddj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtnixqkmcd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtoyblpuhk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtuvwltayu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtfmetvkmz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gttnxxvbzg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtrojbuyih.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtfpxwijrb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtmkolmqco.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtpymrkqbi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtudijqkqu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtbffolttg.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtkeinxqby.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtqjmsjskz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtgkyxfbkc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtwmbzdfam.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtlgmfwcbd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtdnytqmyg.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtajlfhxqu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgzrmnqnt.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtfvkljgpo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtuaaoadpk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtdohbjcrk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtgarazzcl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtimnellbx.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjzjxdorr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtazxypcbv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtavwpwv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwuaqymjd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gthjqghlja.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpqkhklxa.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtniyixlif.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheffweoq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtcnwnvnvv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtujhwhnwj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuaipsqt.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtdqutlaxb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtzjupaslg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gtwnigkcbj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gthjadudhz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtfwggpryi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtdxjbtpkg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtkdrvejso.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtxroubujg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gteuurkvvx.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gttzrtxuhu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtvavoalph.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtmhzjvdpi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtmshennfu.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtlphiivbd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtxmifzmyj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtyqmrjihq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtcfdhkvrw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtbmqfwpmd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvqqhzknh.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gturvpizhi.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtchikaqeo.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gthmhnitll.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtlohbytfs.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtetyatyaj.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvijzjwi.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtnpolcayu.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtybdiccej.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtuhmlzggs.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtuwncyxbd.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtvfdiittm.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtftuxcqre.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtbrbskshq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtecqnslry.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtvqqgqmsm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gtjxdkedls.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gturpnmwce.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gtlfeuwlzy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtolgiotyk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gttbfjyvmb.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtsdprewmk.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtabrrtpdc.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtmitcurtg.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtcjpseasm.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtfktjroac.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gttomiscmk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtyhorcmim.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtezqmfayl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtqapvhevp.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtritjfzai.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtqufsjnpe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtepukcgbk.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtchkgqzzw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtnmrzzppr.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtpqydmdsk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtwwmlmigp.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtlywpcxje.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtcxtqiwdv.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtcomupdti.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtupcdqbjv.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gttzjashyi.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gthqlkkhfp.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtlyfcqkvv.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtstlwckkf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtmzagtqfu.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtneixdouc.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtuixjbzih.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtnwacntmb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmpzghlu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtwnpjxryg.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtghlgcdig.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtpmjryady.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkhaiasd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtjlrexfsf.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gtivrlrzzg.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtfodinyjq.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtysjyswrn.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtevaiglzx.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtuflbluyw.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtswnhkhku.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtbwogemtd.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtvbedmcxe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtwverpvaz.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtgvstmhvp.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtnctjbilh.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtlrkoosyo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtklsndzfo.html


<!-- 参考信息 -->