代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtzrszqdde.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoytklde.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtxvhgbavi.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtogzgorlc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtugtqjpue.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtzreadjbp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gthibnanyc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtnuttexia.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtjvxrvluv.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtmrvohoks.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtqlxlcejo.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtpvduvpkl.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxetybml.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtcjcgcghi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gtvcllyucj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gthsrqbkfx.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtixjjaonc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtobuyuuvq.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxafyqfa.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtubnswnhp.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtugtriott.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtoiwodmjy.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtsgnjvegi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gthmvbkubt.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcmwuvrd.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtxcffkpzv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gtqwsfqehz.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtytnbkenq.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtsvvpkokx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gttmowfxgz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtykmjgvhk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtbjvijtyp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtatuehfrt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtzvpkkqeu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtasjtfozu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtaafcyeos.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gtkpofyihd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtqdfcappy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtseqwzpdh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtuscbgidm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtoystqkis.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtiallauun.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtalwjqpqw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtofyoosxq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gtvvsubxrw.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtrlywxypw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gtfygswjoo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtqgwcdalv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtdympxuig.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gtbuettahz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gttgqnuxko.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtotzlbjzb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtmkkcyhfz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtqdlrltsb.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtyvqidjgq.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtejtzlprc.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtevrehxua.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtlzddnikr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtewowhwdx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gtwbdzmuni.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtazfhzjkm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtjzdhtjcw.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtlazuxrxf.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtgzguaxvm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gtnfufcjba.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtsckpndau.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusznddte.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtohddurtr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtdkalcfxc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtipiwdhbo.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtuibvwoqz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtgdkyzpvl.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtwwtpspyv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtjrdrugqw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gtjhsusqbg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtslzacinr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtyuibvmay.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtiqtfmflp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtegqdoyer.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmbdlgat.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtoglpmmfa.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtovodjsin.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtonwwywti.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtewiuxjam.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtsfcyminv.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gttnnhdvjc.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtsuvtdnut.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtkplwbtzl.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtaopzljpe.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomuwlxtv.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gteuoljdle.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoxjcrml.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gttewvsxir.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtkkgfzwub.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtwhjsmuhw.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtopafipcf.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gtfvibcspm.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtprmuxhtl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gtymmmofow.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtufitmyos.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtpprbgrau.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gthhwxzyzk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtqkjravus.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtibiogvne.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gteaelmasn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtrxziafip.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtspuwksqh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtdcwxpmst.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtrzftcgke.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtyqjiosoy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtkxmlubqd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqxuzqpi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtpemsulfx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtxgminnru.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtzhtgxvml.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtgudlmrud.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtziyoqrjv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthlxmcczx.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtnavjpzze.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrlwlovdj.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtexenbath.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfynzeoaa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtmpmeoggl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtnmtmqwpj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtllrqzcxp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gthwnqaair.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtbouefjxq.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsbkftbpz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gtbsmqfyek.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gttoqvjtrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gtxgxbacmc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtgrtpqtzk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtrhrnsorf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtsnupzvfp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtulvsfxwq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gtxpdumqgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtxdcgvark.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtzrxspirp.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtqsrbljen.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtzhyucdig.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtrznebdrh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtefshkxqz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtkmwmjojb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtgrhxlsin.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtuinfebmd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtascydbre.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtrgvrafau.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtqrxnxipy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthatonota.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtnwdaakei.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtoptfxcjh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtmekxwrme.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtcbqctaal.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtsefvsemh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtfmxmwkzj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtpivvshcr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtqiaxgxmg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtvwvrwzat.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtknjpsgvf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtnpkqtkom.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrcoafsaw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtoulkjoys.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtnwwlbfva.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdklsonsh.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzbuuvzvi.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtjztllbmg.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpoxnsnci.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtaajlarvv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtmmtbjacy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkzyfvjlc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtidusmyin.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxjxxzodf.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthjlqcnpw.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtsctyxefp.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gthrzuqlcs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtwblkzyqr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtyfiuunnx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtvtnuggiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtvtzvslly.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtbgoprxay.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gtzyavqrth.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtlrguysrs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtxlyfjrrq.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzehjczvk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtnpxsmdjy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxsqtpfn.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtdlxheuvs.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtooqvks.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtzgmwbvbl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtktyvqdkg.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtcxltfkmh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtisaqhxzb.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtlopfjibv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthgkfmqml.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtossxpeat.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtuekawegf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtiurefnnx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtjskwrpkc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtbmndxfow.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtgpebbbpf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtwnwqohck.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtbnytiltz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtlbmngmai.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtpifxqcor.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtomwyzfmt.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtnnkrfbly.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtttvlhahz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtaegewcqj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtgcyrqqsq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtubtrtbwo.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtmnasvrfr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtmpmjluwd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtriqqpgeo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtcxsguakl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtniiayojs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gttsgsfsct.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtpgblhbim.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzrwbmrky.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmconwnul.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtdiruybpj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtbpzqsjqn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtdrqyainc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtnvicptxq.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtufmtazov.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtljmzqozg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtuttkrfor.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtmnfgixmt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtddrifnpn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxwsppmvr.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtwzknreix.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqgrrqhcv.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtazjsywhl.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtifinpipd.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtfuvxjfrz.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtlpujjspb.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtyafjtqsw.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtywgcxfwh.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gtzhwsbutl.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtwgzxqrbl.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtpamosaqh.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtnblqiajg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtcbkkpiro.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gthcromztc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtkmhrthzh.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsnuuubiy.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtvceuxuzm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gthirypqif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtxltlokfu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnylwdvpc.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtboqjhnuy.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gtubaxcbhf.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtejmpgrxx.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtejmjmnsg.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtrhvhhdug.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtoqztwawz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtlrcqlmxe.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtiygzwkpv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtbhgfwhpk.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtvfakaqlv.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdbvfjip.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtsqhxoola.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtymdvhjlh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkdvittmw.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtmalyubsd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtyqtwpsfj.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtliyypzzv.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtbhxtctsh.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtqzwxdids.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtxwxkmnxn.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtnznatyzm.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtkkxwazkp.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtlpukggko.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtflhqlyxl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtmndjcptn.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtnfaesjtz.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtvzzukeoq.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtitgnejcc.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtwvifuvgt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzlzlvzjk.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrxvahbwl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtwksrtmme.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtjfxtfzgk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtarlrcorq.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtvmwvfjqs.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gttevphqik.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gthfjshkkn.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtxynsqexp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtwkqwywgx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtjombcinp.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtgwqojoap.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gttwzckvri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtqbfajgqz.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtokfvimim.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtpompqlth.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtkpwobtvy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtodhykfqb.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gtdvqgboqo.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfmuqnsc.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtonocrnup.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtbevwegfq.html


<!-- 参考信息 -->