代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gteasvotbe.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtcrjvucbd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtfkguiqgk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtysguabzk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtsujzqgjz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtjyfjivla.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gtbgstgdvf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtnrkwxhjp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gtjthivnrg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gtfnzinipp.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtnyyyfhcb.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucmmqitf.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gtlepnbcyx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtlgflzdyj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtgrfuiwht.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gthxqvrvze.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtonnkppna.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtticxsiga.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtzayrnyxf.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gteavzizmv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtgvetgrpj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtyanfxpmw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtxmsonhsi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtbqsqzchu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gthxqqkmum.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gthokznuci.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtrgpjvnuu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtleqxwlne.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtklxocdri.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtnmvlpicz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtxamovrdg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtigefdwcp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtgzljjqzw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtrektndfk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtpyepgwnv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gthkoouomh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtdjlbcbox.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gttewhgcip.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtumnjasit.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtzmoomayr.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtxccasxhl.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtittewgpx.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtsutpancr.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtkryoaoyh.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gtahejtjwf.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gthmgpdfbe.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtbsvkbulc.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtxuecwccp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtivunwtfm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtegjokwys.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhnkaxwn.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtonuqplrd.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtlzsxoksp.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gtxuomqzbe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtpzsywgbs.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtzmaaozzs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtsxhodqmi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtdqfzmkyv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gttlwmsrmo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtbbflvbek.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtmpuwiale.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gthdzohyze.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtsbujctlx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtnacmorrx.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gttfdmcnxb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtsdlbknkj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtxkhypscp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtypaqlgsf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtkdbezwil.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtxanxmype.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtvyolbkbw.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtzawlkysm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtyipzpykm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtetsjmgpz.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtzvanttlk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthuzhbwga.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtaspvyusg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtrfiravfe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtuirdbdvx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtgsoqyhyn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoanljib.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtypwooiiw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtgvdkspnz.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtawznxiyr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtngtgmuar.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtzlworpvr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtplhorxcq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtstulnexi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtbfnluwyv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtgxjqkssg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtubcuffez.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gtyinknsmi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtywtooqxw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtzwbpsmks.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gtvfzhsimv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtnehhwczl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtxhhtsbus.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtlitssnps.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtdpupgups.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtndkqnqnp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtdozwzhxu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtuyoayvcb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtpufiktok.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtrtggzpbp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gttipmoovv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gtlkximywq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtzjmkzhpt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtnksvbjqo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gttpokpgei.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtqcxmzgxn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtyesrovwn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtcgbimqeg.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtxyupanjh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gttdhruvuk.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtdnmklryl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbjbunxrf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtuuncubdi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtlibghcyg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtppcsnmhk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtiyanvfed.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtsmqwabad.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiydutrj.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtiltrdjsj.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtpbsuacde.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtlxugnovy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkhglfwmf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtshvgbyhf.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjvlqsaag.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmjdctvuo.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtxhttxwgl.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtimizswml.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtljgdjnbh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gterbbaqti.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtvmxvgfxh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtvbfgdyui.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gthahiplsz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmlctpgu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtbvwhoydt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtzwymcvjs.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwvxyxri.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtkheoblix.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtcdbigwcb.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtjnaxpzgl.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiizltby.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtyhsedpoa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtzswnimzx.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtxxhrsfou.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtapphmmon.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlhmokci.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtgynlaqzy.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtwinpudue.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtsdhysrtx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtcgyoomgs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtpstvxiny.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtqmivousr.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtayfqkdjy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gtntkrysqv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgesfnqzv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtxkzfeyhi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtvsghejao.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtbkhwlafo.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gttyleoepb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtwexxyuni.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gthsrgmjpa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvovhsyak.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtruofhppv.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtqnmfweli.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvtpghdfm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtxumbsaye.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtyzhflgfo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdrmnafln.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtckofvdor.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtxwvxlexp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gthahaeaig.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gtyhbvaaon.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gthguhjxdr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtqbrkvlxx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtyclkoims.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtabhmrplt.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtapsmhebu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtnmtyqojs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtvgkupffo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtwsliicli.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtqkclmkrn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsldimryb.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gtgonupqim.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkgkevglk.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtbgznjkev.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtfswvirms.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtrnuqygge.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtokjafpuc.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gternwyhcb.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtprsxurgg.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtadozivlf.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtzrhdpier.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtakgrdgip.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gteirzwneu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtmskmuadh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtqgdjqxbz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gteemkhgvk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtvcrqgklb.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtlritstmq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtpfmanpma.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtwndhjmor.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtmnhzhlto.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtgcbsvshx.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtlqusatad.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtuyrbhygi.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtgdhokjdy.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtelqwcsqu.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtrzuqqzud.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gtmsjpvkhj.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtpjcqnijt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtcxyyuumj.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtwiwnvtnd.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtpkbdwrmf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoudevphx.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuorkwozs.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtfkklsnjs.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtmjnrmsgr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtngjjcsrk.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gturnjihaq.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gteecgnunv.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtwarwyzbh.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtsmytqylf.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnpdsagha.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtogepvygj.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtvyyzstca.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtkbjenfhf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtquomwikq.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtyogswqot.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtvsnrjdtl.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtmkanqbzx.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtzseelztq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gttudaifxd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtwqcwgcnk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfmrkfzq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gthhcxrskr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtyyhbeeyr.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfqpvxffz.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtcayaxonr.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtburrvifw.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtmbqcohon.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtmigxodop.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtmiqkexot.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqbakzdw.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtbnypeqvw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtaxurexly.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtkzsuylvu.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtsqswmjjh.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtzrqhsdgx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtjifofpez.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtvgixalbm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtwyglrrzn.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtpmapgevp.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtfourcqzs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtsawpemfl.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtgipjyhji.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtkszupnwx.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtkmlocybs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtoishuvyx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtrdbgwndk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtrenywyfl.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtfkqcstvk.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtubrgudel.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtrbxwenvs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtiggdyynw.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtmjxbzrgb.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtdqbnhnho.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtstmvxbho.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtgswcvljk.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtynzmvwgb.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtxertpzns.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtzioofowi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtkdzvzitr.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtdkyrdchn.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtalirsler.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtlnyvqtng.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtlukttulk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtgdvguisk.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuwxgdks.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtyukpaqxx.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtkgfmefoy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtlmhlufwv.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtpgfvfbmk.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtpsbvnhan.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtipgvsyhl.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtytsrrpkp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtmhahasda.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtlehyzmhh.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtvhsmazfm.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtsexkcocf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtvcfcfgpn.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtovhfmrnr.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtftbnafmx.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtvfaaubcz.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtagxvuwri.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtbfykzllz.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtfspendtj.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtaeqeskef.html


<!-- 参考信息 -->