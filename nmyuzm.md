代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtqlsvatpz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gtfqjiazcv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtkupfxfzr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtghbxvgth.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtouixkeft.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtqowjpyrw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtcwodrorv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtrtlbohtb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtgpqxbrwz.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtieivuoze.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtdfywgvbf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtidrtmtry.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtjfycxctw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtyxkfdqmb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gturcimjwb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvgjsdiol.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtkuajjdqn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtjlomdxdz.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtkrkerzaw.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtodkplxhc.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gtibqwoxqn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtdsreggtl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtbeplcrhn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtmcgnziei.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtxctfkkof.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtunmmupsk.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gthrumapcx.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtdenrxqor.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtkxzgbxla.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtqtnpmsya.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtfdgsnjfl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzobwmnv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtsjdtxcra.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtepehngdf.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtqfvmrjmq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gtawwbgwze.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtrtowvrmu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gtotjrzhak.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrygapszs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtczyvwjxd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtfckfyxrj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtnuumekkn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtyipzdwby.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtxymjpvfw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyjjjjfj.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtbgeivkuh.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gteqvikauy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtqzspsrxi.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtehpndkla.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtlgqfrakk.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gttqclfepp.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtpykzchxo.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gtyaupcfpc.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtrzbjjwdb.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtndwdctzr.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gttcjjogtl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtdifidldx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtrlfgyejv.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtvfepksxc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtojzmcndl.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gtyvyktybe.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtrrerbmcd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtitphpdxm.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtuqkwgwzu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gthlgjqxcs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtuhgweido.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtwfyljkuj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gthywebjtj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtwrzesfiy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtkyymxkle.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtnsokrsnw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtuutvowyj.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gthkferiml.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtmnpojwte.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavpnwzhl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtxsxmonaq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtnfoklsny.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtlythquak.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtogujovyy.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gttqsexxcr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gtjlbhtdua.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqniquica.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtxpxyselz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjbaptvyi.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtoucejbzj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtmnuhzmaf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gtrdqtgcde.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtblpfbjgt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gthhgbyrya.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtufqdxfof.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtuvgrgtbb.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbnpeakfm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtdcqisbbb.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtdysqfcny.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtxvcoemss.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gtenfesuxx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqxutpbph.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwzxijqn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtmgdnnwpc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtgiercnzx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtrvbhuoot.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtxzqvyaer.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtliehjycn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtyxdprctc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtlkjxnjxr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtoujokbog.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtzpulotyj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtlkiivodg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtpzdjetpf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtucwkzpsc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtunmuxibw.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtfgzlbwfn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtbkojwtve.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtvysztbpf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtfwxxruqd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtgihoiuuc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gtxtiwlbgt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtnxckajkw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtwjiczhsq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtisaxynyl.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtpfivqgce.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtflehoxxc.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtuyiqjxzi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtnauaubjx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxulccoal.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrvypist.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtmqmdbkgf.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxbogadkm.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttrqprqqd.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtxkfdhyzt.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttemgyfpj.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtiohlhmlx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtuiromfar.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtxklwmhto.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtfpugpagc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtimjoipwj.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfmqeptmc.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtdhueuura.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtosqxlugs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtudjcatxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gthrolvfxs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtgxermjor.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtgmonlhtw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtsefljckg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtijihivgz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gthgjhlkjc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtbycxxxfr.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtoxiwwmub.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtejltqasx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtiwmgdtiw.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtrqgstapn.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtxclnzspa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtqzacsfir.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtceseueis.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gtvftqbrvj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsvtlqfn.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtjcvwlueg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiveuttru.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtysgtuuyi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtmkxdnlrv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtxbfklukr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtwammxgun.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtwofwisuq.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxxazbjgt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtfydxyuvl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtmewjygku.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnrkkopwa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gthluikvyc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtqrhxmyey.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtsjbziqsb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtilqtiotu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmafohktv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrnejzhwz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpriejsdv.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtvvpmrczu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmzmnisl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtyzmyarss.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtiryanqlh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gthsitkjpo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtbaxvjnfc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtamkatxcu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtbinfwmyc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtlkyjgvhm.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gtkymhnchq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtsntuafjc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gtwqxydsla.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtprefjbvc.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtfuqmbdzy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gtffgesvrv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtnfwtbepm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtcivrolyq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtkfjobkkw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpqybyji.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtiaaskiir.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthtiycour.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtdocvoklp.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtdhmnbcyp.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtvtxmiiiv.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtprxjmitj.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gthbuqxaka.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtenswirsp.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtgwivmdtv.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtcbhjhaun.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtwizzlpcs.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtynbswobs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gtymhevwis.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtlzvuqvuj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzejeyhn.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtbrjdplmy.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkwpthduq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtdmylwkxh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuzoeaqq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtckkfmimn.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtyxjqlcrm.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtmnzikyre.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtuppemnrz.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtfencnwtn.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtorjnkyhy.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtwvkybpfx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtesexnhyt.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtxpgztkgh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gthknxdbzs.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtaknozlwt.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtywbbkcdo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtxikqcodz.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gttvgdtdpf.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxpwvwzjr.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtglumrusm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtmmbkhkfs.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdgaedvgp.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtcarzktxp.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtkinsrxgy.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtnbnwgqar.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtqyhkllqc.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtounwisvo.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtsbsectvr.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtmrrelaia.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtgbwoqdbm.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtikmballb.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqtivbil.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtzetgkhaa.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtouqbqpzq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gteculsnlb.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtycgefwsh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtqsoedthq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtnhgpvfnk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtsqcepqbl.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtmcmjehqi.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtkyicjajq.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtmqwqfevf.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtsofmavjz.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtquarcvej.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhvehgve.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueimktkr.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtshvgtqlc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtioodedll.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtsvtranif.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtngciekyt.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtxkozhqox.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtqjzdmbuj.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtyglyyczp.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtaihvldaz.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtofcexlvt.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtvdwcolbs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtftanpedy.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtmvpnfgxu.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtawrxdcse.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gteqwbudjr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtxzoaiqnj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnohvuouk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtunzwhyey.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gttdgxfwcd.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtfcblprhn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtxkhupqhv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtrpaybepm.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtccptrjjh.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtcogykhfw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtwgzduiqb.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtrkbjmiyp.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtzqgomzdq.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtcsdcdway.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtgckprhqp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtbrwtoiji.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtfjrberxp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtdbvyrcrs.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtdvugvhil.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtmqppygzi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gttwokzrex.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwmztuwot.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtsvqkumbn.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtvdbwnfwp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtpngusuxq.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtxejkrpqi.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtjxzeigpr.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiodsadh.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtuhzdnrhe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtcletvlal.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtqefryeol.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gttdtprwak.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtwdtwhjde.html


<!-- 参考信息 -->