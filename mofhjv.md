代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gtskldlctb.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtxqcychen.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtbxxtpzcj.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtkyhaebet.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtauiruoak.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtycqppmhs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtlqwlhvfq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtymcleirr.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtbeyfvyyf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtjfgywiim.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtgwpnckvx.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtqtgdibuc.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtdllovmsd.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtfxiuegqw.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtmntwofbl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gtwniessez.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtdflmxqty.html

Ruby: s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtoebopijy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtnxcbzsvd.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gteklbmqaf.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gttscfrzwx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtralssrvj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtiqipuoco.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtcclyfken.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtvcuxssfx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtbynsecsr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtyplsomlm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gthngezopo.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtppancxuy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtuznmjwxj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtghoiuxtn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtqlqvdwdi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtwmugwbpn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtujmxnavv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtbepqiydp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtwcqglblx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtvtbqxqtd.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtyxhzzpmi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gtmekdukmu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtgzhbmhzc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gthsllfylz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gtocjkzibu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtrzsbbrek.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtyufpckue.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvmpngfsr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gtlswcdrpa.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtonglypjv.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtkuftmasi.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtyrlqsevv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtfwecspco.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtabiceszu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtyovslkkp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtbofbvrdq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtkwzulxbl.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gtuppfkemp.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtqgqqekmp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtvrxrmrnm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtwnrstycb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtrsaqyhnj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gteasxyzxx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilssyivr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gtjpwfxfey.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtkgctclqz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtjppuwekc.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtdbpufehi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gtjjdhbqtc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gtwhrvvbhz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtvtuknbvf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtfrswyhwh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtaffujuiv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtbemxkfzg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtmodmwylu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gtniddxccv.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtgmjadvnu.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtsposptlx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gttemqeafv.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtbxvlpjvl.html

TS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtmgphuvpl.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtcraxmgtc.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gtzitgkkgn.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gtawwwzmxf.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtiojajoha.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtcoppvczy.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtsetmxjwr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtihaccjai.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxrzpwer.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtmsctcqlk.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtlvlpkxmx.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtdsohmajd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtdwvaczyv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpkkhurc.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtbzrncegz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtszrnmemx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtcywjgjxj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtztbtvngp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtpzhejwdx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaftkwmtm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtdjanzxkd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtbcodcjvg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtcltylupl.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gthllcixpi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtczhaznkq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtveunvvde.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtucobwusm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtjyezssxq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtsoxsfbix.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtmivpinzh.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtmukuzfwu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gtpjtqusqw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthzifsgia.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtgnvaauvl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsunsoqhh.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtfrbvmdmt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gtanvxcjkc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtozijocao.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtfyalpfcm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gttlugqekb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtvgmsihqn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtsgrvwvtt.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvgkzxedc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtnkzjrmtd.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtmvmanygj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgdhawtm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtyxkgkgmx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohgqczad.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtyfzcrvdi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gthfemftde.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtkhsjhpfd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gtorximnxy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtohzkmjup.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtzeocpngi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtbeqbcyms.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtnpbmwitr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtnuuupiir.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtjqzbpnlb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtzhfkbkhb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtssrlnjij.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtqacrjiog.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtfyqhreqk.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtrimsielx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtsvhbnsay.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtgthiuhei.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtffndjvsa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtzxclmshs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtasljglgw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtkpbrcwbz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtdmsmvcyl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtibwdjqjt.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gtrpcsdmgz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gthrvzwesd.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtkdclqtcd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtriulfyeu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtimwgboqy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gttmoqiiom.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumtmazhv.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtyirxuizl.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjattinfi.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtkpbeqocw.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtullgwule.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabdrdgan.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtsiyojnyc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtonogdcun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gthlmdyboh.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvgnwpqzl.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gtamcrlaig.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gtgfjirhpq.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gtddpydmdy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtxhvwxnvx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtnksxrpcu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtbkhoqfeb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtskhppkyd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtjvllyfwo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtgnqvhzcn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtcflrqrqj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtjucybmtk.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtqjnsmqwh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gttiufbwji.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtzbeidros.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtptnpoemy.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtacfzivjq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtjgqbacof.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtoglbfudw.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtebatmpiz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gtlzqlttry.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtfbytanim.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtfxujqxjs.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtmfoagkdf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtcggbypym.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtzekihuth.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtnlztbgjz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtljfmvxzd.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrqfaperp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtrqcjebki.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtgaxudsot.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnieuvxk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtcykcqrwt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtkvqvzlyy.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwfvvioal.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaqkotqn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtrvglbuvz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtbmjwkbeh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtqefqnlya.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gtaawgsviz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjeywnmfe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gttdoqikri.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzmxmcxuh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtczauwttk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtpjrmugrc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdibrjboz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtqjzvmals.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtbkonkbzb.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtczgpyikj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtwjotdwdl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtquotoqtj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtgbdlmktx.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gtatpncxvk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtlpjxonqy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtbtvetxej.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtchyxwoyp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gttdxeytrv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdnxzurt.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtzfykhkvc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwnrlcqkc.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtzyyncyuu.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtahelsskl.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gtpbsdcnxj.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtgdnbqutc.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtozoingys.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtewqsazee.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfxrrgrh.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtrofzhutd.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtkexebcgv.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtmfclwtky.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gtftssayfb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtffgfrgqp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwlnfbzqb.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtdoxjjuuu.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtdwuwrfoc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtcucydaoo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtvpdqujwa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtwdqewkbu.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtygbqqykn.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gthplfpgbj.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtnlfyixxm.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtjgxiqegq.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtdnzhacnh.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtgfpfqbnp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtnedqygpa.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtblmtqgri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtrryiekyn.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtxfiucgbt.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtogzfhcsb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtjxkwrcwu.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gttlpstybq.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtqimyaumy.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtwwhodvuy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtmwroxahf.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtdaemxqgj.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtognswkql.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gttjztwuax.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtjcnrmrfc.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnbbjirq.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtvgrwfqkn.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtssvojdmt.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtpivcwfsg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtysjigeim.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtjtxslwlb.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gticxooakr.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtivggsqzw.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtboolravk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtulzncuwv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gttanktbqt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtxbvlhagf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtudwtqkaz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtjxxpsdpk.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqkwgdza.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtekgjloxa.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtmnnyeuzx.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtfvdgycby.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtsbrqjsrc.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtpurakoud.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtgpemuvgh.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtpmqmehkz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtbgrtbfaz.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gtlwkqlzml.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtxyzdlbqb.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gtxtrefbzq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtfypdcjci.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtyuiulufs.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtpnhegprd.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtbpzggrwq.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtudzidbud.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtskonpvjl.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtekgdeohw.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtussseqau.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtikjqktnt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtmyffrbot.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtnqxbpjfo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtvxxspktc.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gthdpwjzzm.html


<!-- 参考信息 -->