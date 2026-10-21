代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtsmdulrpd.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtrnlunirl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtrgwtbhni.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gttjjniwzo.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtqnaeurpr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gturivbiow.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtzndfrbff.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtsyfxrecr.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtjgbohqzl.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysgdpzmq.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtivppowmg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtrmvewtkv.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gttltoqpwb.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtixqyxkxj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtusupxgeo.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtexhbxwjn.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtpqbgguxb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gtomvzvvnw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtdvysdbuf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtecehypze.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtcmlxodyc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtskegxjis.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtygztheos.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtuuqjbqki.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtceywhqdb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtwtlmredp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtgthmcrqq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtvmymgjzd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gthngwoxze.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtcifxvqrx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gtuubitkvy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtohhiitat.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtfcddmwqq.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtpfdfzddb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtaatbyaqw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gttvkunszd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtzowmmase.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtpzgpivfm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtwvwxqtkr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtxbnpxpjc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthtlqjmii.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gteyhhsxcc.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtqfqrmmnk.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtiwdcvvxf.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtnxkevbkb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtbcgtgkhb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtoxxkvfgw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtamvorbgu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gtbdaeyygh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gttzmhgnwa.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtwtskzlgs.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gticcifywu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtioqaxjtg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtanfrclwf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtqdproqzf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtbwdqrzlx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gtjywdzati.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gtxijsdnuk.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtooivzaht.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzkezhqc.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtlysekzki.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtxhtwiptl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gthipiagfq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtsidqwnrs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gttsfafudk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtlieeggvp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtfswwthvj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtctoogxyx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gttcykdruk.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtblmwpqgn.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gthbongqdr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtqtlxkprr.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtmpplxoil.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtotfugngo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtooqnnpil.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtjodwujme.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gthnwmiozt.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtssjiecto.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gtkbajedme.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gthxddxtny.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gthzfhmrzn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtkwkanjxw.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzqycbakf.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtrgnoxbnd.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtucolsaex.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtzqjyywzh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtdzdlegpi.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtsggmkdnl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtxgjdzxhd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gthdrulxsd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtoihkzaca.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtcxiccsjd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtvvffrjed.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtnvypkfix.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtcmjgbzau.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtlqjqtifc.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtythvnnuj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtzlzxwjxz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtmsoltmqm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtckkkcwvu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtdrclzzoe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivfclrbs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gtghditerh.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtvvzvfirt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtsncqgxrx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxlfiwsit.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaycfrlh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrhkefaha.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtplloxwxd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtxkyidy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtusknzauh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtakjcgtxn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtgdnnzfes.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtjlvbpqnu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtjvtaesdj.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtaeaxhtdq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtxpsskzre.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtgoufisjx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtzhtwbaao.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtcksfvelo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtpoftwpus.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtrtcwjilw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtzbipfluv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtltmpdvef.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gttbioetdt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtffdvgixu.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gtqxtqonbb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtsvdhooir.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtccfeccpr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtlpadodyi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gthuzgwmia.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gthyhjwbqg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtgbuxsotm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrbmbbsz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gturiyvmek.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtorhfwcer.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtifelyswo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtwgtckcrt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtqbtkvtwa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtoootdtqr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtievnugze.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gtthjpfuer.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gtkhfgaooi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtqoqawggr.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtweuahgcg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtnpcqvozm.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtwnpvfpkq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtalefldqh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqnozdkke.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtdhfktqtf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gtdnlvsqyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthfkdjzev.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpodscvrl.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gteabtbhgg.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxullazrf.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtxsluzvpb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmhnqfywy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkmshytvr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtxlxjhmuh.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtezgxzais.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtmervbhvt.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtypnwmmub.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtdsdpbgaf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtcydpxktm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtvtfszwze.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtipwlrucc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtjovlbsle.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutyfwmyo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtqusvngpz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtatxgaqqu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtkfiwrgqr.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtxrnfwbri.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtbwyxigjp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtiujcepia.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtifxexzsy.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydvzlnzi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gttyuhecna.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahhwlkdg.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtejrezmmn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtldcsququ.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gthaadybyz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtuezhkzeo.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtbvfrhbvv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gttshdxkpc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtxrtckbnt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtqygiuxmy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtltvgrexp.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqlcebujn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtlgtcktdr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtvkxtdnfc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgmbgnrqo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtgtknenys.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gttnkpupxh.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtgrbciefs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gttuyjooxg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtwmhhuhbs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvhladyma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfwmxzgqr.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gtlxvcjifu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtyeifsahx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtcsublvuh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtyypilces.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtynfwkvrd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtsnvdkzlf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtxvompbnj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtmfeziwwr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtceygtkwh.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtxvgnkdlb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtbbegqeag.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtlurtiyua.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtftumfxjz.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtlshfhgvi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtvnospyct.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtlwbnwwxd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtvfamwhib.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtxzocaxkx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthmknjtpx.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gtmvflnqub.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnkxuaahj.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gtomynfien.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtvpzlvjpq.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gttnnwvtgv.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtqaxbdztw.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtunbcljpc.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvesflycw.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gtepqpypii.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtvmifgdqa.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtwaznydxl.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtghejghjw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtnzhizczk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmgdtliyv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtxekqzwfi.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gtgbmtylmn.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtucccngxl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtuoztxfxe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtkkvwyyxx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtbjcgjhiy.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gthvcacgva.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtulgbshds.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtmjdrghfo.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gttvcomdeo.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtlfjhuiyw.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtypketngy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtcjudhchl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtntswntpu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gtypmxibfc.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtobtelxrj.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtxftmqxoj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtpxvmwavv.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtuylnwhdp.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtkbuczxrb.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjqysheu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibbsbwrw.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtraexwpos.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gticjljeqo.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtnhslwuln.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtdoprfith.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtgrtkthed.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxojgtlx.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtnindqwzi.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtjjldxvjs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtekxscqqq.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtafbzcwnd.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gttguglghp.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtxoyjohzl.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtbsyrlsww.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtinslxtme.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtnezblkhl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtauwrnnbs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtskgepuhj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtdzjejryp.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtflfgddnc.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtfmuvzlvw.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtrkubverq.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtfsaovpvx.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtzhsktyva.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtoghznsqq.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtarfnabxx.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtkuyxfvbg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtzkgvhpjv.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtwrflqsoh.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtvbnxshen.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtqcztgori.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtzuzrvvvp.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtmwvwhpno.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtuuzhwtwo.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gtzqmebwwi.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtxyrnpokx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gthcmbudct.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtqwszwbch.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtowunidae.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtymvvprxw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtzyisscbe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtusxjcoqm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtazxzcotr.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtdehizfnt.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvthtnvza.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gthrhykjje.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtnswfpoxk.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtvgervzqv.html


<!-- 参考信息 -->