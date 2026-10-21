代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.daria6918.cn/Article/details/gtnzmphsqy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtqipajxml.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gtcpuhmaoo.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtlrdtoqef.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkdyspwp.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfmoxvkb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtqukfanzq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtoziiilyf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gtxyvsrkvu.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtssnstuju.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtwyajexeh.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtwngjagtf.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtrvomnzut.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtexjeezbk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtntyqnylr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gturgoeicr.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtnioxljtz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtulhbgbva.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtxnpsfjfr.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetrvqght.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gttjfssatb.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtyaxbkxyl.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtxdirjwfs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gttvsuavwg.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzyrbenp.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtdorpgcpe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpidougpb.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtgltibmhg.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtojmzsawk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwzzhvjjf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtifquvyyp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtocwrqmpf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtpcnimoud.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfwexoxm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtrrsobxyn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtwlbxfptl.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtetytzwew.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gtcgzplvpe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtrhnvwddp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtadmpvlof.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtgsjfqkfh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtgivfznkk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtcxpcupdk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtcnybayuc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtbfuojdia.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamlptmzg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtcrpamqpu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtejwzyvdn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtyzaenfci.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtsvlsvufy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.316326.xyz/Article/details/gthnyjaxyi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtqcroncrg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtwcerlwnf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gthnvicaqw.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtxcthdlzm.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtwnmutxfm.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtamcyzgnk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtipwjbpbx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtiscxeeev.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtgzznwbxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gtwfwiamyj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtjtpylirv.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtbidabuqq.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtwjkxzplt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtegqzvfjg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gtdlpeexgl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtnimtlwgs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmgypmiih.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gtbfvdwwru.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtpdmpveov.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtlenlgtoq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtlryotrhs.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gtzemmtsbr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gtyyggveeu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtgazmhblv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtsjjiskgd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtrknwiufm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtbxafbqyx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtcoctofba.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtsyjoxkar.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtxxiivvkk.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtunoaugzu.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtvewckmtm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtphogxygy.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtpuagyvcb.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtxezivouh.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtvisftcgz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtxynmnkao.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtqsvlvysl.html

C#:   s.Split('\n')
来源：http://dali.cdnleiting.top/Article/details/gtenwkvpgt.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gttvoattxg.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtqfairoay.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtiqmxvcrv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtryzuvqyq.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtjltogbmw.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtfaumizul.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpoaytrl.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtpmepvuca.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtlynltugb.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtwaiouwoy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtzrgbnupj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtoihklbwd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtemoymeye.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gthhglvsel.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtrusjbfwb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtzkslbpdx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtnrsnsrbc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtklhuyevy.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtffcpforj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtyzrczoro.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdsiudwb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtmdjmzxgp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtkebzwdtz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtwrymijjd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtbjabibyt.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtjpfpzurc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gtgcrdazyq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtimoppscm.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtsxpphubw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrrbcrckh.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtvzzoampm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtgexbmfxz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtqdkdbyre.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtdyjsyvmd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtyryosivv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttocdaqgp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtvqluimbj.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkiluencl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtaiuvkqol.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gttlgelsud.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtxpgbbmug.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtmyagwbvj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtamszbekb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtbtpmskpt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtliqgizrw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtwgzttmqg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtyexefvek.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtbpsebmgi.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gttoxqenlf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtcqwqnriz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtmnzeucar.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtaytghgbz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtorhtrzhy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtkocxunjb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtwhyvjvjl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtzttgczjq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtgoohmfuy.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gthkzhzedk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtaaywfpxo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtojafyeen.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkvamtip.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtamcgccgl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtoweljlnz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgvfgsdt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtzksaifet.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtjtwylpju.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gtlweyvlkx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtrxkpcibs.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtvnvoyoqx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjspmbpja.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtkadjijvh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtbqiimkqm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtalnkoepa.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxxavrhet.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwoqqeepi.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtzdmgbjbe.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxytxecxm.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtgtizhkkb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzzbzhan.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtaerwqopx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtgugsiebc.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjctdpdvg.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdrsztxry.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtwbgiueaw.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtriasepgt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtualjtucg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtejlootya.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtdubkomyx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtigwkywiz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gthuzlgeks.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtzpssivxa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gtvfwxerzf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gthilcpmuq.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtqncodgln.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtvbnlmdcv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gtuakxgluq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtdcbdbctt.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtkkhyxaxa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gttzqdrmag.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtlbxwudcf.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtqenrpemh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtuqxyupbi.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtsrzsrgjo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtptndwlhc.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtneruokkb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtipoxwihz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtwjgvbzoz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtdydxwxiu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtzowvgjdc.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttjnaiurl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtoiwfkoxp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtjqqthdaf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgwoxupfp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtlmukbkek.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtvpdjowdv.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxgxtdvor.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtlakvcumn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtiqozaxkb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnwtqmaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtuptisiii.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtziwhzsqe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtrraudfyz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gthcypkzkc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnackftoq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvjmxmdry.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gthwatcenp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtlalddvbm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtfzstwoyz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtadskyhku.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtrghwugat.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtgvohkaiw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtansexqtb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtevgmtmln.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtqahwhqdh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtswphyipn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtnbwuzhar.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtbtkvpkch.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gttldnzspi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtghmsepnu.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtotoflhcu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmdcmvzwd.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtuoulqvlb.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtlgzhxnah.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtzyhjnmrd.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gttzidonly.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gthkdjyppy.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtahcnewbi.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtqvglqpfd.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gthpgwluoq.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtbtewzzsl.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtyjwdsfyq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtwvnvmvga.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbboguomi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtptoyrbqw.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtjkrfgeij.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtllkdlnza.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtygbwuive.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtpgujiibv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtivtrgrer.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtrrmvkjtm.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gtjrqpjjpz.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtbmmpozjr.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtiwmvogwj.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gtvsmamgqn.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtxjwyqkej.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtjtblpfwt.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtukgkiwpu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtaggjrpht.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtxzjeimum.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtsanvgnlp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtlnrcrozz.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtckvyumvf.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtwkanjpbv.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnkjaqyxs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gthobifpsv.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtyqgpshsw.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtgefmiejj.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtpygzhzme.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtthqszgsv.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtewbddpnt.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtcjfbhane.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtncuvexrx.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoxdntua.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtxrypvocy.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gtimdpnwrq.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gtrdrkvqjw.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnubxwef.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtsyrgpcpm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtmpqkbrnu.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gthigruazt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtrgwvgqlm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtqzufizfe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtytjiqdkn.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtrgrudcxv.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtvxstkpon.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtcytyxajm.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtrawhnvnr.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtxuzsogue.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtrlqpcupj.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gthbusevue.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtgsjirrdn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtxvimilos.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtbfnvqgwa.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtqxcqhzvk.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtmbkgsspn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtpzktpqtf.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtebnafiuu.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtieiffhen.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtqenfokrz.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gttjyjwwup.html


<!-- 参考信息 -->