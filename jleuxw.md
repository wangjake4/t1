代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtxosbsaxi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtscpkyytk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gtmbrsggys.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gtjjdpqfir.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtkagzrnup.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtgktxhwvo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gtrvhnewmm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtiniwtzne.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtlblzgtfc.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gthymdzziq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtphdwowbv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtblwjlxnm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtrqksxjdn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtrpmsfwop.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtzjrajzyg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtvkprmrgk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtexoirlbm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gtqdcewnnu.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtmxdqmghp.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhhatuql.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtarrtirai.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtuegiroph.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtjuksqffh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtxebmvewz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtgunbkoih.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtrgzsxefq.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gthbpdlbqp.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtwsgxurdh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtbnwwpnad.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtuesnupww.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtaehrqskp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtumtzfyju.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gttjocdqih.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtfkcubdmb.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtkbzyfvsu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtkmbrtedi.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtujrvmwag.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtwkzphcce.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrrgcjas.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtiaigzevx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gthixwzghl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gteujfojri.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gteojzqaqd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtksidsmcq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbboexqbj.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtkqcuggpo.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtqlqboohx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtezbrsvgi.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtkjahcjua.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gthywiwpma.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwuwrejmv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtlrkuzbyl.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtzjbhvixr.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaosyuudq.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtbitrumbx.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtyglzsqii.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtaffjhmvp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gteinvgyen.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gtdggkpvgg.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttaotmiut.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtfokrkqdx.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gthvcwlkbl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtoyabzvyy.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtkkogutvp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtvsytlknx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtogoztljt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtdiifrowe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gttxwttpph.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtqinstqmf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtjaoiubvj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtnfygyqyw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtmwtqnpdt.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtaqnguiod.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtqrfenfji.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtnqlnpxta.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtxdrgqvoz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtemadqliy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtaxurbrdl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtxvnhzvom.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyodfbvad.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtncheqwsq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqncyiyzd.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtfxkwmevm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqbgbwob.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gthedpdiyl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtujizmfmv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtempyjhtx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtrvpzcmcn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtvyrjjqqm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtlaobyjle.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtczgigcun.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtmoarviwt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtzwnczzko.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gtjhrjsxlt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtjrigobpa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtpqtikwfp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtddxewkag.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtnciiigle.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtyoqmxwgx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gtfmjjiyaw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtmhypvexw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkahqujj.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtgmcbjbpx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtttymniwq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtmdqmyrly.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtiicestbd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtnouzcpjo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gttygfhzdb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtbjnkhhkk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtpxyztyfs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtolomjpyq.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtrpvfuiwd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gteetmyyuk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtvmlgtgzy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtcatanfso.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtntcusisz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gthitdjydz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtdhjgsgap.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocyjhqjn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtbwhmljtc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtekvivyzb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjhzofcg.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtwsxlikev.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtdpbwhhvk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpdlfdpjn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtmkcpbyuk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gtgzsrcdtw.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmtrtquqk.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtvfmksoca.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gtybsgavvb.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbrxvxgkk.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtlzqizntt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmhspbdla.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrneufaeg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtowrmqbkt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthistprla.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gteghwepbn.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtdxjnqjls.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gtfqifsuwy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtnscfrjcv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtwsgsbgrq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtdqbyexzx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtteocggeo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gthosbwsva.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gtmujdnzsd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gthukbavhg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyjqspvb.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtggaviyzz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtdwjjxnds.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtuhrrzurm.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtfvhgrqff.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtriwayuul.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtworgacvi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtvdzirqrl.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtqlyvznxy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtceztnaqy.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtfrqynuwk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrgqiunoj.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtyzblkhez.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtezwxnvoj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtvvbuswwb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtklyrbwco.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtspydauwj.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvunewxua.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtvehonmng.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gtuzhmysmb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtpmtfowws.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtxtvrgqqm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwblzifxf.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtmpnybmhc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gthbhbbmyw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjhskltgw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtcohyhvbr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtpiqpcmei.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtzuwszwgq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjfxbqdjp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtmrgiptdq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtxbiheqmp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtzmmnosrq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gthgqtvzhh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtffzctirh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtydaqctqa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtxbohhqad.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtoiadegys.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtzrzwkiqd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtqapnbqki.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtxdqdbskw.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtzeulgbtj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtypsrnncj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtoloaeiku.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtsedzpjks.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtnaelnmyy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpirppwfn.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtmoboqroa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdvzertzm.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtbunaezse.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtgunjtzsv.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gteewhahul.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gttcyipxww.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gthgdodlgs.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtdnbwhrdj.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtxxzcweuk.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtvnwmzkwg.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtthssxohs.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtesunlcfv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtxlowtmdl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtkkotdsty.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtssqsobwb.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtrbmrofpi.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtdjotapcw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gtuclyedbj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvkaanxra.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gttuwgouja.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtuswdnxff.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtuhxoblvn.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gttjcylyky.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtsmfdklhc.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtmiwfpdyx.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtchqrcmix.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtfucjiuwv.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtjwxcxqio.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gthoqjyhrb.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gthvcgcxod.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtflrllreo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvbjdqmc.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtvkspykpk.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtnbqysucz.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtaxaeuaze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtqetdatqp.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtaswsoank.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtkcsnuhip.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtdmqvmbnx.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtmtgpxjjx.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtfzvquqjn.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbmaowpf.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtmcntkhia.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gttcsmlazx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gtfgubewux.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtnfgycozu.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtjsfvviav.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtrjbwiofh.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxqmssrf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsnakoxoc.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gthxfydflt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtqxtoowov.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtukspxrwq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtqifhtbnm.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gthlnqyscb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtwdaajgwq.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtzchmfswp.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtwtrajcze.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtkqwyqjdu.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtudhtmybu.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtpwbozcsl.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtjscbwbqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gtxdqtskqh.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtcwzwvlzn.html

C#:   base.Greet();
来源：http://dali.yvedp.cn/Article/details/gthalxrspd.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtyklducgj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtflckwqzh.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtzshowjtj.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtnsuxhvxr.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtbvraynii.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtcbyepryw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtkxfpvsva.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtgdtqsrnf.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtrslpbadz.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gthwzaonoy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gttobatsqo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gtowcmqwcy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gtqgxawppd.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtynergeea.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtrsusncbx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtgaxuzewr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtklddvdoj.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtkqjkcero.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gtuwzdljdy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtwrlkbnaz.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gtlcixqkap.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtdxtofswt.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtjllbgfsm.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtybnziiqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtbuhhrntr.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtuqteknbj.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtoijwwlxt.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtydsqzuac.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtqyglldhe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtznpxeetc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtqtyslqfs.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtwtdkprdo.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtrnmrlowa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtytadpvyi.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtxryinixo.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtkzqxveng.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtxmsyjhvl.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhnlecay.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtkyhtutvj.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gttsqtreqh.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtoymedeae.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtcyxcvyxh.html


<!-- 参考信息 -->