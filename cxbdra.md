代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gttimmxskb.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gtsedbewdy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtaxeklfmv.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuszkoal.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtnvdvexrv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfcjnhzv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtieydceeo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gthgrozynm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtixkzkrdo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gtxhbjggdf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtlulewkyp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzhhlccsd.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtkumivdeg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyviifqi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtrmkkgnes.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtwtjiolsk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtckdpohgu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtjbljcizs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtvjdytfzi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtwbvcusgp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtpahxpjdq.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtuhhpbwak.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtmrapslke.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtiispjwcx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdmjhnbbl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtkflfydge.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtrjshwqsz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtliwzrfry.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtdzokjtld.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtbkczjyca.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gthfkfmedy.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpxwntnb.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gtwmwauanp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtagoqbdei.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtgutvekme.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuneuinmv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtiornureg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtdgoanxzt.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gtkhxhvmqh.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtefdjwzkg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gtwybmyuvh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gteafxvswg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtnkvitfaj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtmqjikxoe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtitcbnjnq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtkbpqwxxl.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtumaczqnj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtjxnzgmne.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gthgxwwbam.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gthpqhqwun.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtvqaaowuo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtatrhnicg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtochuzmyx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtgudteltj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtctompbcd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtaijxetvf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotslhbxv.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtshukhwcu.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtpqghuryi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtrfnzjpwm.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtfnzsiety.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtmktnssne.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtliirmuzg.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtjpvlwsxe.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gthfpdtsmy.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtwvnkgdsi.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gtaifwgpoc.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtvussutfe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtsbeqndic.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyckocka.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeeuazfq.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtsvcplcqt.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkslbuld.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtvmtoxork.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtfojhqpst.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtqjrvcwnh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtjstejdfl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtiowlqglj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtkgaejsrx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtnuiilsvk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtpavomtee.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtblfpmemk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtpjpexrqe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtfreljzuv.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtyaqpuism.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwgrtivbz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtngpqiynm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtzjweegoh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtwbtjtryj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtzkjovyte.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gtfleqciae.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtahioxafo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtrtokkamt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtauxkurjj.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtaagpytle.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdyatidvr.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gteuxbpbkm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtonstngjg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtuiuxzbpb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoljfullg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtunpqjtlv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtgnammkdl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtgiwmxsrl.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtjugsyiid.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqctmbqbo.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdnigoov.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwhkjxhp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtsjskhehf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtchloaury.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtvswzcvsp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtmipykxbi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtsoyhhhkl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gtsknjuwjc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtehuskraw.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfigyhezn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtmqqqwbtz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gthhnafvkf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtjraypzdu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtzwuqjvmm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gtetyaaxdc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtgrzvlhrp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtlnuhllsq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gthxmlwvia.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtjckgoxuo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrdbapep.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gthreksnbk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtvdkynjpd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtfnaerpra.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqbcbhzh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtfhqljkbs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtjrhmbgdl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtfhvwvodl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtfwqyklcb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gtludyozxv.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctfmxalg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtlsqdjgrd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrfmqxrsv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtnlczhxfv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtcmrlpolk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpzkrsov.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmuzrwobu.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtmuvbkyni.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzhbmemey.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtfomhidxn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtkpwpcbxq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtojisjvov.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gthquzzuvu.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypctrzbk.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvlooqvpf.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtaomczubl.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtorfvdckp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkfclgbw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtcnxgmetj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gthejhbuhd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtcqjpnzmk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtszijgluy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtpjdhpvrg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtyufrstyv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtlkjfpcdo.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtyzgxhiaj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtiytojjbg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtwvixjcvf.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtvqvzmkof.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtxyqhxwzb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtvacabviy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtwiyzgrsr.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtglwqhrbf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtnpnbcual.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagzzpgvh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxzxtxlig.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtbwfgzpfl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtmwjonbsb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtchfgndct.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtmlrbmnhl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtbmwemnqz.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkueaceko.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtoezcfwhn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gtasogogpu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpihrbwlf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtqtvpompw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvurtvffj.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdqdcohmn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtmihbroxv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmaruvido.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtgnlrkpbp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhyhkzwj.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtklyzlppz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtozpgfknq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxkjmsub.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtndpeuctr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtaaizcrhb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gtqsxuivth.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtpnamjwna.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtnhwqwncu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtegoeisjt.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtjwsbpmkn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtaocpjznr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gttnbamxhw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtysulzcvf.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gthbhgvkyw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtmqdsvlee.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnpmvokj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtnptzmmks.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gtmjumjjoy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzwsbosdu.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtwoqujhjk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteprzsrpc.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtemgytzcg.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gthlkrlaro.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtpfmsbdzj.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtkcraajrg.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtavujvryb.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhrvbeuu.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtjvtcvwsn.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtouxfytmg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtbdgyifzw.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssvxphjy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtgjcjjlwn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtpffmxtbt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtxvhpcbrk.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyctrhqol.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtummcwgou.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtsfujmoqb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtpfcsanqu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtocdozodl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtzfhgruff.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtciptjdpu.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtotqebcfo.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtcjnusiwd.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtqshgrkuz.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtkgfaotjm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtfrndaekr.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtdjbzfsej.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtmunpjugp.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtdysfiltd.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtdyaemyni.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtjpiydtko.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtmdfqcgpx.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtteigxksh.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gthhgmcbzu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtgvhigiji.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtqdlidtgg.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzimbgtop.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtiapuslrv.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtxksydcxn.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtsyyrlxlj.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtxtqtissf.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gttkyitaye.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtrlsweuju.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtwxhiefsn.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtdalatpow.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtmtslargy.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gtgmekteim.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtuhbmqavg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtsnklimye.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtxmhtanyi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrdyleue.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtazhjphwi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtjieiyqff.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtggnkjpck.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtwgvhilfa.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtzjbangob.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtpynpptcj.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtbjceqesk.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjbwldem.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtytzkymiw.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gtgikunuqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gttxeocecc.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtffdvgupi.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtbeoabxra.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtlhkcjeij.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtokrmsiws.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtbzggataz.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtdjykouvt.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtxczvmeic.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlrxovkmd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtsvvklszw.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtrvmfbxbh.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtsywwlabm.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtjklexycd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtiwurlgft.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtfduurxdi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtuuedgchb.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtjhfkvwab.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtqzrlkhwc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtgtoxoryq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gtnxxzcxvi.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtbeiavxlm.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gttzchkqya.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtvybngcce.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtuldsdpnz.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtdwufmfwt.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtaqoioqam.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtkgowwgim.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtdwrunkmy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtwkbtimiv.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtkkfusoat.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtujahytys.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtkpxaccpu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtqkdegbmk.html


<!-- 参考信息 -->