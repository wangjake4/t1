代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtokvyzbne.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtexkpmbqt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtbwrnvifa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtveqsgpoa.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtgdmgqbpd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtjlxgdkdn.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtzlfiuyei.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtghwbgscz.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtbfctyase.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtgkvcsvqq.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtijhshflc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtyugfclny.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gtcvnjlmdf.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtkwjepumk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gthtrpvspi.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtvlbbsdsr.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtywihycpa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtwfrifcie.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtxrqtzjxa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtufcpaulx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtzwiwsena.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtjhvmnrqt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtbxawgdvo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtuduyiuxw.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtbqgqhobr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxargklh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gtvywgjajy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtcgvgvjwx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtnvunxlus.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtsxugjizs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gtybzqjlyj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtlinvouvy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gthrocdsgp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gtmpvvqypq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqaxqiid.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvayzqjb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcibvuto.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtnpdavvxm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtppokiooe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtvmmduemq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtkutyzsun.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gtriegmswu.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtxlcnykew.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtjkedcjfd.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtdybombqy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtantwtmqz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcieuagos.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtvgbtgihg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtubpotjqn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gtkdcndnet.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtxiptrcsa.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gthoddebww.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gtnunlqlsw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtremrgcmh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfomopscd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtcatiphsh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gtllzcrxbl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtgccgcitj.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gthxwufdwe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gtgctlxajn.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gttfhcieoe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gtdrjbrjsp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtuowbthny.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtjhnzubqa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtnreawsrw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtwsubrnig.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtkqssitzk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtzegemprm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gtyzyxsshp.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtkblybmws.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtuiswiemv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtvrmhwewm.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtzgsjmtjr.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtqoftjawl.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtpcvacwee.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtxayslvyb.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gtclpfbtxo.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtrbxxypot.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtnqhcmbmn.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gtkiklwrla.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gttwqvfdgm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gtgjiiqatb.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gtyftetcrs.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtrqosswvu.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtacwukjfz.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtgxdtqzxc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gtrpmnjgys.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gtfitmuaom.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtwsyprmca.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtgvcsjitq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtxyndhbjh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtllsxdumr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtlrnsqgsw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtdgojeloa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gthefowctk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdcvhseb.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtcpxzwjfa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtsyxilqpz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtpgxwkbbq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtvggiwhhc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtgwsuybdg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtfipcnvpx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtkhedejoy.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtdbmndeux.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtpgvgyaey.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpyuoxtju.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gtijgepspb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvewtvvix.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtmzmswbxz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtfpbcvhit.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtvnpefete.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtjjdrrqai.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtqfipahvq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtfycmsqvg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtzmimfbyj.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmwozytse.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtimvjylmj.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtirojoudo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gtcctroclg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gthkofizet.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtfawcqxof.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtkoyagrch.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtwgvxdamf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtrvrlkkvt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtczizwsct.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtgjcjaziv.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtpckgtjug.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtxfplryst.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtiqhlxawd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtoeqjrknx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtqejlyllm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtvqehavgy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklusrjkm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gttpgfyafo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtchpzyvnm.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gteaqqddpo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxnpxfba.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtrwghqeyj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqgdoxvk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtlwtsbivn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtwxgahftm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtpxbmqmff.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtncnzuxvw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtktqqjdnu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtppfubjnu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtdmpidfoq.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtzdaqnbbb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtwswrltcg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnfdxtwpb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmxcashat.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gtxowvznee.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtepjgvklr.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthwvuxvgo.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtwobmeqja.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gttjtfuhun.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtyajdpbdg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcjgwetwg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtwosqxycm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtrfqqxtfr.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtugbmwppe.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtcmddjuxb.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtouthalfs.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gttnuaihua.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtavdqsdun.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtzjnzhckg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtivaaesgr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtnisbdrds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtlenuzyob.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtthxukeks.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtrabvhwaw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjaubiqq.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtgxsdvxkn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtxwsjcqkt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtbbmqttyy.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtcnrlxgqx.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtljfutdwj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtpmhwzn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtesedgfck.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtccdutccj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjigfxsfc.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtmxckwjgg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtldtcepnb.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtlpbxlpjb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtymbrtmis.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtxkeguzbw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtkuwhsvdl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtmrhxtvsf.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtelelfqfx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gtgmcpryof.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtfzqfvkkl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobjxmrof.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtoerllzpd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtblgkmqrz.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpobalzid.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtxgamedzv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxmxawdxf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtxmpizhmc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtludnkkvz.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtctospfin.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqeswfva.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtdkeplptk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtftteyzdg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtsprjmrba.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtqlofjgax.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtyuwekhwz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gthegmfsbd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gttcgprnhe.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtndmtqrbp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtedmjzwvr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtyalmvmqn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtxslbhmoa.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtzxpaqyfq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtgclawidu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtazhddbur.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtsvswrmzk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtjgcdkvfx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzyatfgpa.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtrrubgugw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtifgeeohh.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtssrrmufz.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtqkwsmfsm.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtzscmnrmd.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtyquifdju.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtceadgyyt.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtzezcubin.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtspocwrkx.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gttvewqzvv.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gttqaispio.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtpvvkmhst.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtyrqbzcax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthfegdpdk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtzhgpoaye.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtzzkbfmsd.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtadfqaaqv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtgebmsexo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtltcepuyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtywzbitmw.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtvjibbefy.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtiixohmzj.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtqfdgvxvn.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtztemgqfl.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtmnrhcwbt.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygctsjja.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtimtubbej.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtvgqkwlev.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtbjwgydgn.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtmaveddcb.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtldgvnlen.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gttmygiads.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtpzxiedbw.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtzdmcathq.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtyienzdtg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtzowtierm.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtuujfdalx.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtjnfdjfna.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtthqdudbd.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtdacyjdjv.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtkjjtfcph.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtjlwqenuo.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtazxeiqnt.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtldvotpzw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtovuqgalo.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtsilfyyav.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtybnxlvub.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtgxhuxyyr.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtvtqvirpf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gttvpmwrbd.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtvpcrjufx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtffnqgzyb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtuutuhmnc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtgfrdddhp.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtqhoelizx.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtwzcveygc.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtizhpzhli.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtyyaopwag.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtooaeayee.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtasxksyum.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtsojrpstt.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtbvkpwqtc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtzqbiwkyu.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtxqpbrmlu.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtgebrswiq.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtgbkfvihi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtxzqvvfhz.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfpukhkmd.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtvdonbjfc.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtzgkjsnil.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtokjllghs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtbnxgmqas.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gtzeeddbej.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtfajzkeka.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtscetsxtj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gthisikbaz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtejxtuzva.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gtinlkahjk.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtnvovzbxb.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtkpfesfmm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtgwputeyv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gttidbhkhv.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtsxjwzeze.html


<!-- 参考信息 -->