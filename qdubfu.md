代发 wailian999

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtkmdgcizh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtvgpujqyf.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtiecnntrv.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtqqlsxvfg.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtgdnuijoz.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtlmvcxkhe.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtikzoaijc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqwxlfst.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtaziltmro.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtnpubwmzf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtyawwvgwg.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtvjuaubye.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gttsjyixvy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtxftzmbio.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtlnrlhcks.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtqzhbcngi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtxbnvzgds.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvheqvda.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtvnogmhkr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gtsrkjhcux.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtujbpcuad.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtatgfpdip.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxnwvqjf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsdjwjmf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtaafmwaoi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtxdzvrnab.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtbzpuotfv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtvpkhyrzy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtajcfnpdv.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtlagljuey.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtkimsurai.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gthynhkpju.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtaiciygln.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtvgbtyswg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtvzslsljg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtywfxnytk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtywbrydef.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtgiyuywwr.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtekivcbej.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtrggprzle.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtoaqifkbp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtnokxadze.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtlzbheixb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtjsjiurky.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtmaaozzbz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtqomnmwwe.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtzhryutsg.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtgzmrpuvi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtqthvvtha.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtadbbuysv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtibzusbid.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtctlhpose.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gttndcefvs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gtldybjkqy.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gthaezkanr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtsmrhahmw.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtulipkxwt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtevszlujk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtoezdryvy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtfmzlbent.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtimessnvu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtxelcktpn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtjuadfhxp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtmxezulro.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtqxzljibl.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtproihmhh.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtvoekgpfk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gteuwfspik.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtccmhjwha.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtspujtpba.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtlbjoxkea.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtkdgsddrn.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtpbkngcce.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gtmseaeapz.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtztkzwogm.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtadbejgur.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtowbdadan.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbacrmyh.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtbyzgapsl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbovpbfem.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtxoqqezbz.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtbevzbwjd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gtfkqinfdd.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gtvcehjrui.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtkhngxvub.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtjbwtpbxm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtxhwedcpg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtscgggbyn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxwboomm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gtqhyzobqp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtpnystxzz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtwtvbtjbe.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gtfcbokbay.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtazxgzdfg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtddvshdai.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtewnslmev.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtaodbrrfp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtvpcjrfsw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtokvexxgp.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtorreztek.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtizlrqoxw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwmjlthja.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gtstagbcnq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuwdocqnu.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtsmwvasql.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtbqwkwozj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gthytgdmik.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gtntufrgmg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtylwhplio.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtxiziehet.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtzpfgoive.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdpehoemx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjbxhizgf.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtaqapuhmy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gthborztmm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gtwawwwjdz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gteiuwzfxd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gthszsekee.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtnxlgqudd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtcsnmjwoh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtexuwxiqb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gttfkcagvt.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtgxexptyf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtrobcytur.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopvupzsd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtrlgcflme.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfzlxlng.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtydknodbi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtellsituu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtaaasfnuf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtivqmdhdj.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtwfirhccp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtpbijmbqa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtvozbzbdo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtcdlokzuf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtprwyjwlc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteplzaehu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtcntwkvlt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtltjailja.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtngpmtwui.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtgknuvdgu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gteuawnryu.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtiknditsl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtuyneztvu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtopxvqhwb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtmxfoymkd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtravuyeiz.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtsjamujmm.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtnhqjijdk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtmnjcihsg.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcueuehds.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwogmleaw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtqploucym.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthoqxqctg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtmeispykl.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwlmymmmc.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtepzftlxs.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtcgtpdmhm.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtrcfkymtz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtvysohami.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtevdohdsp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtjtjkimwq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtznaebyon.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gthrvtmide.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtjqqebssu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtaicoomng.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtxphahzce.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtwznbnxzo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtddaroogr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtodtpiavk.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtdwkkxvto.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtlwumpfez.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gturbtrciv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtavpingji.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtvpbfjxxk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtkfxuxomf.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtkfnahdmk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtmnzvxesc.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gthqvthphv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtqsythhls.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtlxbiznvk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtkvikgnpd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtnwxocxri.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtblljgqwx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtvxhydojh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtswahmond.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtubobgeyi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtoxzihagt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtameesljo.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtxrlzylvf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtbivhvmvi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbntbfswa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkwzmwhgr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlhlahxre.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtzmbuatoh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpzpoklrt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtdarqfoff.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjupywnmv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdlihzhbd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtjdgwupvh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtqbaoemao.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gthsqdalmj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtmccxgnyx.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtefmrveup.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtveghwobi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtznphzryf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtbikvjqem.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtzzxxcrdu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtphwbeupi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtqqkylnkc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gtdushbofh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtkcicmrst.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyqhpfusg.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtqohtoect.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbilcwlhe.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtrvneimzs.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtnbknjawg.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjydcdquq.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtuqioqrqv.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtwcxwaaxf.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtdbtxbskz.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtvkjtgliv.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtgfeyagow.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtbyhbyduo.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtztvyazfd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gtcogrvxxe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtfanxkslr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtvvcpavqv.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtqdctqodo.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtdqcptcvg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtrwbayiid.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtherbnpbt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtbomheuzf.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtfsfbcqkv.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtylipdiuu.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtulcoeocz.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtkgyjlhkt.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtbsnrxrpp.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtskrbrves.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtpwttihad.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtmogzrvlq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gttxgvmeqz.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtckyhkvph.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtoomfednw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtqcsoqdqr.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtquvkdbri.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtddboahuc.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtsppdrerw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gttmqzrtlk.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtpqogsvtm.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtesdfgjtl.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtjgjnyszm.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtnatrdhug.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtzzoicfvw.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsewqfyiu.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtbzojmbwx.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtftmpssym.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtnmgxzyhc.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtwtmexpep.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtszcsxtnq.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtxwphfgew.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gthogyalwo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtjhvajinv.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtzvbyftcd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtepdkvhwa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtkaitqpbu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtmwzrxeho.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtifpicjsb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtjrsuafkd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtnfbfpffi.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtkjhrvlfm.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtaumnmuqi.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtglazdvyg.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtnimcgilj.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtmzodenou.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtqtdalsva.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtiozzljuj.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdbjjjhu.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtqledtghe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtckmhptxh.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtgvnlekcp.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtooiszsgm.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtxwqrsggp.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthuazbriz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtldpighco.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtttuhonrz.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtpuoqvyxh.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtncmxtson.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gthburyeoh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtetvzrrss.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtjjfajyvi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtafeditbq.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gttxdekkky.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtnqzzouvv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtxashwtdq.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtauujjead.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtjdepystn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtloulecbh.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtxmrsfrjx.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtggpqxngv.html


<!-- 参考信息 -->