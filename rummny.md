代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtomxybesj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gtscdkjnif.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbguqiqd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtftwuiyns.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gttrizawkc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gtcoiwsuru.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtmzfwivej.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtfdaxnttj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtadqwhpga.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtcnmresyb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtdwujxlim.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtwkhambke.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtpasldmyi.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtmwzjotwc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtkrjmhalp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gthjmpdpnj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtsfditkpc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtgqfhklwq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtrypvddvf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtjusvqaiy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtqwwwqzpg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtykxygpem.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtlocvdpir.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtjcgndbom.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gthtgxchoy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gteeubmqbg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtsbzdjcjx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtgniuwljb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvccvmzhm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gttjfpjowp.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtcemdcmqg.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gtlhnxodls.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gtnfujzfej.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gtqjiqeyma.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtgkefchcd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtjwnonjuj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gtzsrpictz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtqdwkmdhw.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtsxziwgyj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gttlmvfnsh.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gthgapekrf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtbcusqqns.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtkllzyfht.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtolbduqdc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gttlsscgsw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtwurostck.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtjymzadxt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtajgaqzzd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gthrowqfii.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopmvejlb.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtzqmpouhe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtaefobwxg.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtywbxymqq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtyaehanvu.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszrbuiot.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gtdcosivse.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtixwfwxyu.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtnibdhldh.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtrtjceipy.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gteohwwcnn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtlvkzpugo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtiemhjzcf.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtteutlphj.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtcfmmbdto.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtwzkzeyts.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdekimgx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtiphlkxmu.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtxobpiuhr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtmzxkrqfe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtnspxazwa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtfjzbxxxa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtmsiimvsr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtbdzmfmon.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtrjqhbufc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtfxqogthn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtpflpwcca.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gttnfzdqpg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtzcxluyjb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtckffgdlb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtvbwknfdc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtcuocppyc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gtncapqsmp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gtxarclziu.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtqcmirczw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtncvopalv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtllgjcvgi.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtuwwnookq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtuyxzhhsm.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtmjguondu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nwbrower.top/Article/details/gtwpdieczy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtveyfgdrx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gteopzfdyg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtvpcwhicf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtvqscaokm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gtiqhplukn.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecjsvrmx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawyqgskf.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtkcqljlmi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtmzioxkrw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gtlczgvpju.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyqxqpra.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gthljephem.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtlcurupgn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtjwsknrtr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtnvswfelw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtoukvkezr.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtgiagbkox.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gtpkqztkqq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtmqttdxaw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtifmjmbrj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtfjcfgczu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gtdhbitmoq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtxljimvfo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtdbtykqxt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtuogwscca.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtgitkjpnq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtnrgbumyu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtxgipcldq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gttqbsybzu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gthccdqgap.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtlorhlxga.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtdblzslcl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtisqobquh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtjgpqckeb.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtitekyqwj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtrxmgbarh.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtxvvaakas.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtoyxlexcs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtmbfwqhvu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtrzofxltb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtdtfvquhr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlvvgfugr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrofvfhb.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gthhapvobp.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtolrptqzq.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtxxibolol.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtcrnaocbc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtazacvujo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtphllpeyw.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrmyhmfgj.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqtosokev.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtvzqklyim.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtkznbcprj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gthichcbsp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtjesowhzx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtxkpsrjvb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtmiwnonfv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gthsoranga.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtyzkzffoq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtulwohbqi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcafppoi.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gticodfsmx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtbwasvpnx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjecpktba.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtpjmxczqa.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtddehfqvq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtsjbnyohi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtdcsvtqyf.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtbxvwasnr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtrsefxnqr.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtgwfhnhhq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtusimlgwc.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtobnlscdm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtqzyhsoje.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtthchkwpt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gteukukpkb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtncoiorar.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvrugzrco.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtsaiuivzk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtcjupyjbb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfwofkiol.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyyqaedb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtljjdnirm.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtshkgitff.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtrarhnwqz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtcevlxnki.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnkixjdjq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtxpjtturh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtlsscprhy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmaewzdpx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtouguunnf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqrhsgyde.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtklncezbb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtsqkuypml.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtotetdatd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthfwibkiu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtrpfkrqqm.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtcphqaqoo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjqkleea.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtnvfnsgju.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfwoackf.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtggfozgkr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gtrxkiepgk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gtivrpyydy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gtzchnzekk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtqdehgyrk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlgdsciwx.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gttktlxcfz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxjlmyhiq.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtyavidtrj.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gttocguddw.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gthuqwytta.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtgodmsugy.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtbymfgkds.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtkvebmqjn.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtjjcsyamd.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gtwjjwwzdf.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtraklzxkv.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gttbjkfhei.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtxokgfflw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtaxnyogzy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtdxsbdimz.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbhgabdwo.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtnqrilwsj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtilskbvvi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtxaoceyez.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtywyfmapx.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtpkzgjnau.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtosomomvd.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtmfujptug.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtcdelxyjj.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtakwxxpej.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtcndvdalt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtshbxivsa.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gttvuipyql.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtvnlosyrb.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtvfqylgos.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtvwxdbvhk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtikhehaaf.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtwnzbfzmb.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfvelbnz.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gttysifpsu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtbzlfcqmo.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtnlhqoqml.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtairhesmz.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtairulogi.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtveykzqwi.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtfwngtavu.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtlwcznzxh.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtbhfqubqv.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtpzhnwwlc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtnsiniinw.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtzjhzdhqv.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtemydccxe.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gthplbjdwc.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtbovymgzp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtvihzeisr.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gttbjgtbea.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtvfkuvqar.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtvbwggizi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtldhsopzq.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gttmalrqri.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtuijhbgrr.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtilfireev.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtdoysnqtl.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtnhyspkof.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtxmcooabr.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gthjuwgrwo.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gttslnsgte.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gtoxmohrok.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtrrwedzsi.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtiofpjusb.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtmxshphhy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtzvziguvk.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gtzzarurvg.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtpjortezm.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtnxmtdkgw.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtknikpent.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtraxlxykk.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtjtymzuog.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gthwkyjqyf.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtftxhbgha.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtjkvwvjfe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtsccmqwog.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtstardwrq.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gttatvitkd.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtfxaqekok.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtpfxpmcrb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtgugxfgrf.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtzprhbbrm.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtoedqadtx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gturxyijsg.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtirkvfeig.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtxynwukhx.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtrtybvrmp.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtvysucesw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtuzixmxeb.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtftfnmblg.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtansictyn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtudfibcqr.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtzzdktfvp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtdhuijumi.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmbuchmmd.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtmwchqvbp.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcapjitmv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtafebyudh.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtlinullrv.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtojywuaxn.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtshsjvtul.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtxcpkykmr.html


<!-- 参考信息 -->