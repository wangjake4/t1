代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxcvqmmu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomoorshq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjzwqxlu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtoszoqhkc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtfihvuror.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtppjghkhk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtmpmujvdd.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtikvlkaqa.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtmlaprwyb.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtdoledwju.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtwpyggbxy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtmrmnbhlf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtabiptnfq.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gtejlmoaka.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gthxdbfmga.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtyfttmpce.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtsfnibxar.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtnqjcsnzb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtlbecbcrd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtlfbzxdne.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtzokbpyvz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtxanzlkvq.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtxxygimfy.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtcbhfamdq.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gtpaadjrng.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtnjhfubit.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtqxdpqcxo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtvzzfbben.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gtdpkbuflu.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtyrvaezdh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtmrvcpxpj.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gtkaanuthw.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtwuhkkjwk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnznzfnsi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtietdfvip.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtzhaoukdx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtunhtutwt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gtndoeqkly.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gtryoiyjky.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtcnxipwhw.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtdfdqjztg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtvhermvsg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtyqbmhlit.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtwgmghmaz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtofxdtnve.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtejnaeiiq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtqwbuwzdm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gttsvchesu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gthalejjpn.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtmotdoxrv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtwmrewbcl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gtvkbegmue.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtptemuysh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gtovqrqvgg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gtsadbrxwa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtykybpmsm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuanzhike.top/Article/details/gtmetrnzlb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtkbzoelaz.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtaepechvz.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtbhjliydw.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtnykbjmiv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gttqeejfcd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtmkvcdcun.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gttlhkkipl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtvkbybovv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtifenksxl.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtwivubpre.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtktlawykx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gtkpwhzllq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gteqoggwxm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtvvxfpznb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvmdzkxlz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtglnywnkp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtentxlayd.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtvhknhdsg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtuofrafbr.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gthxtltclb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtvdyatlyh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtnyemdodx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrozqeit.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtlyrwaqtv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtxdqcczxg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtvwyelola.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtcecevfwz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtnnyzeibl.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtgifrfnir.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gtbjopawqm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtklanqvbk.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtyqcdtlwp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxvchbil.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtqyguncpl.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gtsfrrqect.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtlxqumsbe.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gtlafqhloi.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtaxvmgjup.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gthivrkyuj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtgiqerpei.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtwiokvstl.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gtyrxyobrw.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtsysggctb.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtfatehfkj.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtislgopqf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gtbawxglfx.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtvayvnugq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtgouxfnzq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtytvtcjfk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtfwtxsxbz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtwlhlhcjd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtxiziwcxe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gtjuoiless.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtfomarqgr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtueqqipia.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gtbfszzpje.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtpnfckxna.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtjrmwfbbn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtnzphrjds.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtnixcdcdl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtrgjmqemw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtpwiedvzi.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtqdxieszg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtrpwnnsda.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaludgjkm.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtswsdpkzj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtewvfvpyn.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gtbnadrnbd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtuofnwpvy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtpivydwmk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtelhwxsxy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtofesnosy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtpjmzvzzp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtesyraeur.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtinlawifd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtwykugapp.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gthtdspxjh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtetwbilrl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtipnzybib.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtwkxffjbg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzwoulysj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtmtxyvmxu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtvanqjblj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtsfljedsw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gtqgmbluxg.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtetdyuagd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmyzjatg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtozgyawmk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyefdxjf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtczivnvjr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtwjutzsft.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtxgdaddlt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtwspczfjm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gttvhkewlz.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtffvfqikk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtpbqavgfr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gtpndxlfah.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtytjyiahn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtrwxrztve.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtyfzbygho.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtvvbhakvq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtvnorgbbl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtogzkkjkl.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtmpqljzvq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtmdcjeplo.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtfyokkisu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtnpqopaoy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gthsoqrqzq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtbiwxromh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtgqmhutei.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gtaxniimjj.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtydtyefll.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtiaafnlob.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpjsgenil.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gtuzihdbcx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtlwxbjfdm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxbubzujr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtsbeapokk.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgnbydzjt.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrabdsbav.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtsmqphaji.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtxhhlyppu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtzpvqanpj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtvldjxmpu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtiphfzxah.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtokdkdquu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtbngiloms.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtfhyepcdc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthhjabfr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtijjkiutj.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gthbinpjml.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtmteolakl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtnnjrgwuj.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtjuovavvf.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtnzmbumif.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gttcysfism.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtccxnhojv.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtxeyubeqj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtxrkvfwcq.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxrudwtb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtftpnvvls.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtiziyvkkv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtfkurqyvv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtaojsjqaw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtuupbknuv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gttpmifruw.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxoabdfge.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gtjmpsqvvv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtrslsybwz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtnjjatzwf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtvwbqsuqn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gteeqwuhee.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwigeendw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtcpnyvnly.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkjqeqhqn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtrlxzxmtf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvsscdzfx.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtycinlcmu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtrsltpekz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtdutkfkfg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtykmnzwjl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlbzrqbjz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtplewmhks.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtzobxbspf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtoxgkvcsf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gttvemxfnn.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtkktebhxf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtyhzjtoon.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtcxolbeqe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaqmvjux.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtnbxtfctq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtkthluaao.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtmknsdbrh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gtmxgevfgu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtaxugvzef.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvskrpiac.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gtdkabneei.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiivptaum.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtxhocmkhp.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtcsemqwbw.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtoptxdmnd.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gteeoaykie.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtidczqset.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtwftqgmtw.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtyndlrtia.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtazpkluxo.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtmwgwlhxx.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtqehtlxps.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gtzdmlwwuq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtucwbrnfn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtojypcdvj.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtxbkykkqk.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtivshocoz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtijshomza.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtqnncpfte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtdkyicmao.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gttqvjbbwq.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtelllemxu.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtpxnfqrzb.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtvwiivsvq.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtstlzyukw.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gtnkaarzji.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtolgpblom.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtckjzyqmn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtssmtnlsp.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtitozpfse.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtnknjrlwr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtezhcgujg.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtucrsgwzf.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtpwvswwnp.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtjvwqggni.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtzadwkizf.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gthslcsmxu.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtqjyfutzt.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtofydoyml.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtccpcugbr.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtopndbjcs.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgophfphp.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gthulrvilb.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtiajqekki.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtmzmxkyhi.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtlajydtnr.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtqrfzwhdh.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gttqfytoew.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtyqnrxtqs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtxykfltda.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtdolhtvle.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtnicpvsvq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtxvxxocdu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtsswhmnec.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gtsjhczrqk.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtzksziozg.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtskwvhmco.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtgqtcrizw.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtmiyjjsty.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtotlsapxr.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtoubrxuiq.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtzzrpkhvs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtxqzdcqyx.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtsqhgvdzg.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtdjonaagl.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtwoywgwmi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gttxuqptnm.html


<!-- 参考信息 -->