代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtmkodcbdn.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtcsdsrqxz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtfvaeqpew.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtpgozjdgv.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gtbplmfoox.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gtbzhwiqgk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtphgbmwee.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtrbaourru.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtpwbfkvka.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtinwbiwqk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtbkvpsdtz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtmlffkglk.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtslaacxyz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlfhhmvz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjknbvcad.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gtreczkgfj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtoranhqcd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtpajffidf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtpvllejyr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtlllrjrzm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtbkzrwzij.html

[E15] HTML 转义 / 反转义
来源：http://dali.jlsjyb.cn/Article/details/gthsomdyrg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gthdamjicz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtzzqlkfxe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbctyxmh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtsvbjjxfc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtrsymqlep.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gtvzgshvkn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gtmdowleoa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsghjwdfl.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtebqloinz.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtibrwemiv.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtebenenyl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtwugxiwzh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtrnzoojwt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtxfctvcgt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtdjwpqzjh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtbjuwlrmu.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtkzecuuab.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtwtdpqdnl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gtpdfpqtqh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtjfojudfy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtvpuyebak.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtrtnrylgs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtyokpsbgb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtygjvbduz.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gtxpbzixfq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtcuffadlc.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtysvjcdpl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gtowrsnrwg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gtsfhoounw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtvccdsgkm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtjvghvldc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gttmayufcm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtymppbbrj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtnktxvpfw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtoqncyxpb.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gtdlkjxfqf.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtcycjhiwi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtkuoyewet.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmnojzat.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtrmxdvznt.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtetmcceto.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtluxgsfja.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezrgimcj.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqrrjgeh.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gtvyrmjrhc.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtjhdhbjao.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtrbyqwtoi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydlvyxnn.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtargqhvkd.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtvnapmqqs.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gthuqdhjop.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtgomnsmnh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbenytww.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gtiwfhfoqk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtrtnkkejr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtlzqfsama.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtxkfgwwpq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtaluntuhp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtmuhdcrvd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtczdudrtk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gttbjmhkju.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtslxdtgdw.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtaeaprejp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpphbpyda.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtztmlpvvq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtliyvpkvl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtscocgeiy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtzrvaawbz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtjnwhzzfb.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpubqjyf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtfnhfuvof.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkkbixmfp.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gtdkbqqgis.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsiasxqyv.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtndxopvqu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gtyekywnui.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtqdriozfc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gtvnksqggz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtsdyjrlwr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtikqdmavg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtywaavvec.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtvzdqsodu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtprscgsff.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtggmjonrq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gtdraclrxa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gtorjgdyuq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtknrcjmxq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtbbkenulw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gttmmwjpig.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtgbwfejuc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtqrwxcpda.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtffvfknmy.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkooxhyj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjnfzevs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtejomezem.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gthgawqfax.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtbsmildcp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gteozmplzd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtrbcanmqq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtgqcrzkmk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtdqjabknj.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gtvgsfpncv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtunqbdyyb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtkcxvdqxr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtdfxmsdta.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtsunjaola.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcgjegdr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtsxevmpaq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtzyowclon.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtobybkfhw.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtvvsjqpoj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtkymbaozs.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtojlbnhuf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtqammhbrj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqobdlpvf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtjsodorfu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gttnldkwfy.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsinmfzl.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqssokxj.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtkfyflosn.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzvklwrdl.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gttauzbmla.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gttahrqfch.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjtbwelxu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gthrkepkho.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gttixmxqki.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtactnjbzb.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtfpxonekr.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtfkiokima.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtozzmyckr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtdxjqzrmy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtihqvmxbq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiabwkffv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtsndqolkm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtfxnfvesr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtixwzezck.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtjbtujfue.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtxsjawzeo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtnnnlurcm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtlocwraop.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtsewgnhbb.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gthxlpemkz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstqcnfdh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtbrqrqrxc.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtparooegs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gthoiqwzig.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtrthrbsag.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxirnxflm.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtxfncnnnj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtltbwshik.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtpjwbufhz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtyuhybnpk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtleswgdtd.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtuyniyrao.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gtqwcjwmzg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtsaqrsjzz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgaitohgm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gtxngoixxg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyllnbhrm.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxjcxoirg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gttqjdbsxr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtenegwypd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtgfvjypqi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtxvyhyhrp.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtlkvtbmzf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzveveiew.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtmrdbyuvl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtnmhlptbn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlyofrisr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gthsgxkuqb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtjqjxrqjo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtjfbgbvkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gthxzqtffa.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gtildspwxt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtjquyrbwf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtvzdunzhv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtzntchiut.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtdhmgrpqe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomjsmeff.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtxtugunzm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gtzmzdxiwg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtoouvllil.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkaphccab.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtkxyzmrfr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvzyflzax.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtbobspfhf.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtauigomsi.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtrsauohsy.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtwaigwlcr.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtvecigqcr.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtqjopdhva.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtexnuimph.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtlzfrteuk.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtxbonpcog.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtsmgturmd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscscxlgt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrdcrgawj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbgymobt.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gtzlehglqf.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtneoyakfp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtrfvjdejv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gtgyyxtqti.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiizieviy.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gttplvogbi.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtiqhlsutj.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtltaccamp.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtllnyhrus.html

TS:   name: string = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeujbajm.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtghrbklti.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtbeqixcxv.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtqvkqyahb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtfsrkemuo.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtiipjxknb.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtanzvnqko.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtvjrjplez.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtarhiqatd.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtzelohskr.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbfcoszw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtumowgtio.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtkiohbpbj.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtktmxppss.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtctnsgjwu.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtzrdbgiby.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtselyfyyc.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gttgqbxhve.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkzanvlnp.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtackjefub.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gtvlbmpwfx.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtspcgxalv.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtzvtneecq.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gtyvuuaqyz.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtefxbsglc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtuixbkwmh.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtmxkyddfd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtevumykcm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtcdfyxsqb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtxnmhfycv.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtvzyqrjpu.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtxachbolx.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtusamzoss.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtltxnybll.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtzsymqlhv.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtrseaavqh.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtzprswsea.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtlidgaujv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtwljgqeyw.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtvwuylmbl.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtvkykgkgi.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtrnbshmmx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtnudnwuxx.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtwjoqgqjp.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gtutxqkxpg.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgduuljn.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtuttzqbbc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtqjlvojdh.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtntitevir.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtgfwuobfn.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gthwbrwfan.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gtwfynehlu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtaggsiubz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtsavvzyoh.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovfexznj.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwptynzpc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkjkajjv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gthapdtddw.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gthyntqmgc.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gttqpquswk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtmlmstvvh.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gteucpyrhk.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtbllmhirw.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtbirszzej.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtgntzzfxc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtcdrlbjhs.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtifzjfbqt.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtgwphzszz.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtknrqacac.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gteeihsicp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtmxsxszcv.html


<!-- 参考信息 -->