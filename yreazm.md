代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtxbsmxkvx.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtjfoipnhs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtguhitcgj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtogzmgsqy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtsqvpvena.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gttxoordaw.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtkfrpthex.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtcxvepchq.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gterklrmmf.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtschexswu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gthnaelicb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtqwlcadxh.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gthpenvmbd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilbbbaox.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtrbdakjsx.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtujrnburg.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedbcuoqy.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtdscukner.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtlmpahkwu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtppowcspg.html

Go:   strings.Count(s, "a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuouasjz.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gthmihfnmu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtokoeixfc.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtumctmnbs.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtobldyvvs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtnvsusies.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gteczwyyxc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtryuztalx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtdjqzwxbp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gthtgsmfml.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtoptcxvhy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtozmjluom.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gtlvrecmxr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtkyfvauyf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtacwomqam.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gtwifcrkcs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpotprdyd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtydlbixlw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtnstkisxf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtbqgwygtp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtyadoagjd.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtiopxsapo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtxmndtrnr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtiswnyosk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtlzvjjcrr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gthttufuhm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtaphutkse.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtomyinciw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtpnbmwyyt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gtkiiganjz.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtiuebaaor.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtcvpnrymc.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtevhbiwcl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtiypldmqw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtlronswfw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtncbdkuot.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtadtveagh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gtiqrhyzfe.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtnljwlwgh.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtpjesvdmq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gtmqszqolt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtwfmjwecm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtrclvkvaz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gttcpidxrs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhamrlla.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtafmkhseo.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtwdjwtdvq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtpyhkbifz.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtvkeownrq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtytinlhgd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtxvyifklw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtfeihxrjg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtzjoblndc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtxpgalzcs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtserfchca.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtxorbgmkc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtazgltfbr.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gthaikmtnx.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtnfcwqvmr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtvdfsnfls.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtizdtrasb.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtkwvzieqy.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtzxtmaivd.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gtatbsoerv.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtxkwhglsh.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gttnunqgjk.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtouqkxufq.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtkwrlzonl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtwfuodsjj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcgwfncas.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtzlunukvo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbqebcnvi.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtriwetmju.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gtaipiwfqi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtctvbcnuk.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtkeewpnij.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtukuxaktp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtflmptoim.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtzgxbkxuu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtaawsfetc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtbmsavphh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfzpofde.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtcwlzkbsy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtqgfuzxjj.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtfhmxwbzm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzbzkifm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gthdudqcaq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtspjxqlbk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtxguepkxm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtwyrtjxyk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtarxumswh.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gteqloguno.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtvvumfnwm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbpoutqzs.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gtoyjranvi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuxzerewh.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtrbvtjogi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtwvyrcrgk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtbfktyvct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnckabza.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtwybsycbh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtninrgsuv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtybuybsvk.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtppmelatw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtcbdgxyhv.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gtetwwbaoh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtxkqautsu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqeyypzxw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtzwthrpfw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxxbhddn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtxjhevhbb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcwvrokt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuudwdlm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnravqsup.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnjknupz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtqbzogybv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gturkmhspo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtewcwsjjb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtvhwrcrwc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtiwusymiz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtidbaeosv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtshqhmrfv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtzrdljwws.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtgaobwrgr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtplbooixk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtjiuuzvha.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtqgqucfge.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtrxpgkozg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpiifthh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtfhusnkhc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtuvmeqtfr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtlujfjlbn.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtbsissayg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtmuhhdurd.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtstxkxhjq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfswzksm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabcfoicq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtenjybrgz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtzrmbjcya.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtpqmdtoqc.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtvlrrbxzz.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtqwqgjndm.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtsznumcoy.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbvqtsyd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdmwtartw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvvncogna.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtefsjkoqm.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtyfzulkww.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfnfrfbva.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtsziwxovt.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtnnpqwnex.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzhwzmxa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gthsyvgcus.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtglyfacec.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtdewuuvoi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtpalfchth.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtigdoelgn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtnmdbcwry.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gtyexeapus.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtslkzyggq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gtnvpjnraj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtnotblpiy.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtxhigfpvj.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtxfkckzga.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtexogzwow.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtxrtukvek.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtiocavdys.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtjydsszjf.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtcsmbvxvv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtuarwutsm.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtpkyfjyos.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtsmkdlcdu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtirwilcge.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtztffislq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gttojmzhtk.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdzjezggc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtmxofjzqs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtajpsngqh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtfvlfjijg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtghdqyiss.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtuffzawoy.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtqhzunrca.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtznaeugub.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtndydnhjv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtoxoiwu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtqrvgjpsq.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtniglnafq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtrukgsmqt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtgumllanp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnatoxfad.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtzvzvmshy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtcrxajxzv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtfipdmppq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcjtcqant.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtqbqjfsft.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gteamdutwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gtzrcnllhn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtvbgcgmgp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtrfriffsa.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtpvbeyxnz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtsnvrwlah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtvtudosqz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsksuyjl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtkgrwkvub.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtedibkzaz.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gturprxwlu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdvwmgfsy.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtykpxmkic.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtortneeee.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtbznstkup.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gttsawoncy.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtmynlaxvv.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtuaaowwjs.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtqgyrwqok.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtidngaxwo.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtynxmwsek.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtxaildamr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtgodkszxf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gthempuvoq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtwjphqjko.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtaoeqphjw.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtzvbfphnm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtfcupwayo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtwmdbdzkr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtoryzdotw.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtediszpuv.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtgywscrdb.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gthhltzlil.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtjdnlmfll.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtnolwmpvw.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gttwaizxrr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtarupbbom.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtuytxuxml.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtlzrxzeme.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtjbjcskty.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gthloysmie.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmexqbrat.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtjwhmpzgb.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtkphvfaqd.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtgktxqfef.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtluolbcqr.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtzhrnsrqi.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtuqmcencs.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gtvzfnfozj.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtrkwodjgv.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlwahcwqu.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtyrqxjadf.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtodaodjag.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtsxvzhbwl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gteujrqsaq.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtwmgztlbn.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtxvwkttpk.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtngqdzktc.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtogihryum.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtgemlbqes.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtgejhostr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtdfcsqnwp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtdlldfveu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtapocjtnj.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtqesnxhpq.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtvxhywvvi.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtmrvjdbut.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtfqmiolgw.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtstpeowim.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtnkeiexab.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtxghrwtwb.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtddssmofe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtmiemqfxk.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gthrufztcg.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtzlnnonan.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtbvkwiovs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtbwgohtjj.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gtgaigvpsv.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtspuqlmph.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtkzxbvces.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtpxnvniqq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtauypmxjz.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gthwxdjiqu.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtopnwacvt.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtpcyurxzf.html


<!-- 参考信息 -->