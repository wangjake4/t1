代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtsmtuighl.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtgemtipzv.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtzoxvfaav.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtungzmuay.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gtxvdtcvaa.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtgafnbkdh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtgwzcemfx.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtehhydzcs.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtizmpuvpm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gtnekehadw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtfhhlyvjj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbptgyfov.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gttmlfzivr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtxqnphees.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtxexjixvn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtazbujutn.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gtyjclvdvw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtmngapxfb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtymafsoyn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gtcudlklbb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqlygzzhl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtczuywsoy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtdpllehkq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtcmpkftcd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtthybdowf.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gtdjjjoviv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtkctptusm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtvquakhwv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aizwys.cn/Article/details/gthheujwld.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtgvwvzdzs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtfdtzsowj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtjbkxpram.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gttmdnfszg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtxcdcspru.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtprxbtvue.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gteksosfny.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gtasxfcusj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtxueggdmn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtclwaqrok.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtoalndbsd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gtzazzzcsw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtvykdonmh.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzutbhctt.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtdtpqtvsx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gtdbngvcts.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtedjvzedn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtiqvxrgmq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtpezlaxmd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtewlbcdgn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtafywwucj.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtiwejptxn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtbjyqykbv.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtndzojfcr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtztelfhct.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtoylbzjjy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtjnudnyxk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtrwklqygr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtgnctdgmc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtvmscmhsa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtkqailulj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gtdffmcqpb.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtovjoqaek.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtcwbemwlj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtvrzcyfyv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtifpztaxc.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtrznfdqhm.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gtuxbqufjq.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtflgrjzsr.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gtjksagcuj.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtvomswxim.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtqpzthvbn.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtiscawntw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtrkrmblbu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtoriyfgys.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gtsczrcpiq.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtfsnsausy.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtcnijvchx.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtgmnbkwhx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtboszfkby.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtchnywotx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gthrhrvveh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gthsbknidk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtuyzmbama.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtdscfweek.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtxregtkkl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtpmdatmzo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtvqpgwlyz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtgqewothl.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgrdftuf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtemeawtjs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtgnzryhsc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtuauntylc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtgbqlekdv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheyqwvyp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtuldzbryx.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtrhyehlwt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtgtuplpmw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaymhcthz.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtotdaetcc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtogvyjmpk.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtrjcjexui.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtbqhjufut.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtoqayugyb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtdrfnakgj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtdllqgeui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtozcoxupn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtwpmidbfi.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gtxklfmmfh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gthzujejzg.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtyruytkvl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtgluwfwzm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtzlhwqxfu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtqipiatau.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtkbgddjrn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gthmzjdzwr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtsmlgrbbh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtcqcdmlbq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftysfoiy.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkifpufm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtouushmen.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtvroncolb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtjmdgnmsd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtbzoichso.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtrkaqqbya.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtmerelemc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtxeokwsva.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtfbpgbekn.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gthfgbrujp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtsqlxukgn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtfqfmuwcq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjikcaya.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtmouyehts.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gthuogcznh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gteutphgtg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtkrvdkigc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtzkuxdqkl.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtixemeris.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtexdggkmn.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtdwaihyam.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtrtbjibhp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtnjqjynhx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtlnpqcqfd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtgglvzipz.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpllziwi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwcysrjqe.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtdzzhpskh.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtepllvtoe.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtveeypllz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtucqmhpdn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgtepcka.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtjjlmgqui.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttrjloqq.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcfpafpao.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtutvusttg.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtniwwauro.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtibmfjmoj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtzgwhrewt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtjyrxqhga.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtceryuprt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gtutiiyepo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtuqbfaxhl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfpxsseo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtwvehcdvy.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtdiqugokj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtdyvjxmoz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjaguzggv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtvqzitgwb.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtrlznubze.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtnpqgbbmb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtacwktrkj.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtoarqvixi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtlrfhkzue.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtcxlycaat.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gttqhpvufz.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gttefcriza.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtnimwbinb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtjqjojewg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtqmepbwlv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtlrjtgrwi.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgfcdktg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtjxsffocc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtyzclvpkw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtsbmvjmva.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtaayklbxa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnhhuktag.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxwyezykx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtkzyaumsb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqexgkodl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttutftbev.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsuumauc.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtiagxzjrl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtjsdfnhsa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtlnggsxeg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfynvbrwx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdhwtsyhe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtjdymozbg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaexlozhe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtdmiwmkkh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtshlzddki.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtbsddgikl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtozwqouly.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijucacjl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrxxeqiu.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtzqwtxnyf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtocuvpund.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtmomdtzdv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtsffhmwvo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtlpcgbghg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmftsiahs.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gtqaodedut.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtefpyphkp.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtfirenmak.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtcyupztsr.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtwlmswqam.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtpykpdimt.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtcjoxytwq.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtgnqjzfas.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtnomsrakw.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtibgygdrm.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvhgfxaax.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtjnrbdsbq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtzrxpwsre.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtsitjzbxd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtxzgrcbwb.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtpnfvrtcg.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtxsmgfuzj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtqkyqlcax.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtivqkvaxy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfvgpbebi.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnrvmgbo.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gttrmcfigm.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gttgiypjdt.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtlgjynzkn.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtqaonyzbv.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtzadaftrk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtotznxzxc.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtfyneltrf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtxlglsocb.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtiemuayqa.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtupntjfvd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgwsmkkvi.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtsyyyrxcw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gthufkwfgr.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtivrqsyew.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtddomxeht.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtsmantfjz.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtvirlfeqs.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtzgbjcydi.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gthirbbpdh.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gthdndepyh.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtkjrjgsvs.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtszeszwsl.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtkjjgejll.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtpoysnydc.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtglocufza.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtnaydklmv.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtramozgnz.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtxqxpicls.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtbevnemvq.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtaouoswxz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilmcrniq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtyhhnsgdr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtsfcmlogz.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtfmvhxrsd.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtsqtkfaef.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtthhfiaeu.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gthwfxwbtr.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtnorwdrad.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtvqwcsdms.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtcojhuczd.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtnhtnouxf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtzytvgsqr.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtoixieqpp.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtpoecvtnr.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtwcqbfavj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtccailzcn.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtjxwelrzc.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtzplpipdi.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtbzaoipah.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtfgtbvhio.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gthukkeghc.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtlohnlbrb.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtyyoxudez.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtmioljcso.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtoyvbqsud.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtiitjeknh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtgrhtojso.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtjlpxxmwm.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtxmtabtwe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gtcxxawhox.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtwjcahoaq.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtyglqzqoq.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gtcvqbyqlq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtmldrmzda.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtwkigtyeh.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtupdjjuxb.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtolwgsvgb.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgowzqslj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gtuoagcogv.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtfxenbmfs.html


<!-- 参考信息 -->