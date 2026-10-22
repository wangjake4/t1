代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtufyszhaj.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtetidlnda.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtbjkpufln.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtbkkermry.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtqzjjnoro.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtsqqeofju.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtustudpkg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtkeuqnrtb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gtgpefxatg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtfpykopys.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjckancvk.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gtnkwlfcgy.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtkhwbuyjb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtdqykbkfg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtpkjxloip.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtalynxjyo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtycpphlnp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtvktpvaxs.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtqapvyaft.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtwdllpdej.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gttjrcfrtj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtvcmdgowz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtqrmsnmdj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtpuwtbscd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtdvaeturm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtyrideugh.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtgdqjkzgh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtroinbemh.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtlgkmvjsy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtktfalgno.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gtrqtmxwjh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtvyzmuudf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtizcksysy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtdnzbmmix.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtnlyndfpu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtgpphjxfa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtmqeswcbb.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtaobyqclg.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtpvoavcuc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtcoltrwfd.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtwceqcrwd.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtavxvzljv.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtcpibqgmh.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtcddbxyka.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gtrcwvmrtu.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtdabqdofj.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtplyeucqc.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtmpkbubjo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtztxqbaeu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtjaockrmg.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtgezlhliw.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteureovpa.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjzaewgdl.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gtzqgoomfy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtnuqilock.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gtnpnfcqza.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtlardbsxk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtvqwdidjc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gttijmrrox.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtuqwkybbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtazxsjpsz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtpmnlzbne.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtragxhvez.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtepoxhrwe.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzchhunus.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtspivmlap.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtpgryoguy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtzpgkqbjp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtugdjkfxf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtuysllbpv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtjusdffht.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtzbddfmxs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtkhhzclzr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfsrlygvv.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwjgqjzg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqdtocuyf.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtsdvjbwoi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtvktzrrla.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtlfzydbtl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtttspttra.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtifduofou.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtcddwsvpq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtdtwnffcd.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfzolsptf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvutdbaxb.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtfyxnbjvi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gthjuornix.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtocxdcqum.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtirmdskzo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtnavzbcvy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtffphcypo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gthkbmolnf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtloaasnej.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gtprolsnzk.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtsnizerxm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtneknvdtf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gttvhhbcac.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtfzaamejv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtrjdwtzjy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtyxhwbsnb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtlaoxhlyc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtlyxynqdo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtyypftxjq.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gtdbjiisor.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtwvlzkddm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhnuotdm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtzffqvqpv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpibbzmdi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtoszvknei.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtfrlnrnpn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtzhujsoph.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gtbownbfwr.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtwcaadoib.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gthgqjzfax.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtzizatxxj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvctdfmiv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtpqhrjwun.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtvcaopwkw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtgaefdeqw.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcpuvmpnm.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwbpsxwan.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtxrtjiraw.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtqcvtuosz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtuazcliji.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvjpwkpvz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtjvrnghmi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gttdrobzxt.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsgeimvca.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gthwgrbbnx.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtobyahvsr.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtvhwdxihj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtznntzeeb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtyrccszrh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gttjdbxjsg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtllkdfujv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gtibubkdmf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtghgopbor.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtsmyovdqm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gthrygaodb.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gttptivcuc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtwjocbihk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gtssufbcyi.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtpelnoxmu.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtrbxlqhav.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtouazpuzp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtbkpmydme.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtpzyfrwza.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtsgaqgqez.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gthihbugzt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmgsaymyr.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtyoqjwtmt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtvxlvacxl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtmzjixyad.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxojswhmm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gteidlaiyx.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtjhtjnvrh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtrrwneijd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtjucylvul.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtypbdefbj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtoxuzwkls.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgskyiliz.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gttjgatxqc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtpyczupoq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwuuivexb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtlsgsltnt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjqhdilkc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtuzeiokgk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtsnqvxmwy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqsckbeqz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtdaxnpuqa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbvkqgjdu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtigrnwxcj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtlmfxrymb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwqpdxed.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtkoppyrrj.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtbdznznks.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtrlulentd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtjejrtlsa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gtkroghkvj.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtpixjubce.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtnznljogh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtnxrcwbas.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtxwuveisw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtdkjdqtkb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzixmvyqs.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtwsiectnl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtujwjkixk.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtcsprfjre.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtfsftxkhb.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrxfssudt.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwetaxhpj.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtiishrihc.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtbqjtpydt.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtaytimncn.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtuxtnzbnu.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtobjfnrla.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtbyhwwrji.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtbndiwfrt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtlomdtieh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtrplfctbr.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtvkvugjeo.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtncchkmue.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtwhomxjar.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtbcrlvuha.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtzfnwnhnc.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtoeuzxnny.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtrtesmway.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtulumfhmu.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtfsadzqet.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtmgxbjazi.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtbegipzkm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gttyuaijfa.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtmtdwewul.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtcwmaqgdu.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtikskugwd.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtrsvifhbf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtkntnaaum.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtsezshnig.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtblkwjvbk.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtdogffxct.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtyrtsdcgk.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtlxtmxkot.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtjzgeypxw.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtozemvtdx.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gtyrymbzzn.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtmkcsnoaj.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtvyecencv.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gttgdwdbje.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtsbnqwzvt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtklxtsqjz.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtanroaupx.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtjdcznczu.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtjafkfqai.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtoddkzpht.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtqrlbovit.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtzofamrgw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtajlnyhud.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtptpqsdga.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtmwwlyald.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtmiqgktzh.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtqdtwmsbz.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtdhkosgof.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtfqtchjvf.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbneetriy.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtbvbkmvzj.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtqmkwgcan.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtuladdylw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrbvjicy.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtmqglejss.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtfndpnijj.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtwndipjsy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtuqdkdgaj.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtvfpoygei.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwenpywmx.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtqjymvwyw.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtojxnyfdf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzexmczv.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtlkgluvmp.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gttnzayczs.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtlohcfujg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtxlrhnpux.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtrnhmvfbk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtapgifmdi.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtsciotusa.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gtlebscaec.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtirbsszbf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnhobkft.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtkxcaphcy.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gthkhacieg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpepbkhno.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtsrykygwy.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtedvxnojx.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtewncsrds.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gtpmcwxgbg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtkwnxyxbh.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtxwfrqnri.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtfvmxasps.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtbzhfkzbv.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gtmhjzgown.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtslaonsae.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtdigfacnl.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtghibqqag.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtwsfzhyoe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtjpyubqjg.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtfukhbhge.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gthctpcuvk.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtgpvuaonn.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtjnjvthmd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtwkchltfl.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtztrsmvpv.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtheregbed.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtuovjzbog.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtofvvrwce.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtbdbgaols.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtxyyhpczh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtzfxuladf.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gthniobtqv.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtahecufzc.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtjhgsxyel.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtkkyykbfj.html


<!-- 参考信息 -->