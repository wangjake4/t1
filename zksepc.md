代发 wailian999

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtcidqvfvr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtkyoetexo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtndxtrhbb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtuqxogtju.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gteqsuerre.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtgsqhjnqk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtmckaudmg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtjrjqetmq.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtzuaotjde.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtrphzblsw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtyfjsewvx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtnponobbu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gtjraszddo.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtuguazkxc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtsdjlngtd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtscqazgyz.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtkslysulh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtgsrvtcej.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtnzdjaafg.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtyplvulev.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtbaxhgzjb.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtwsslqqwx.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtsiuzokvc.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtuqsrdfyw.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtdpjiwzmv.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtlslrulkx.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtpptlremf.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtndbetvsu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtfjffioel.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtdfjtgitw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtdkecnktr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtzskaovln.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtldyhualu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtdmwyhcpj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtrpvvpoaj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtrwwyuxrg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtgvjgnhcn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtjspxjjco.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtvnubjhep.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtqcpkjzms.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtzzblydbt.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthohgeeyo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvssefdkp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtfktknbhj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gtsjexxqmo.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcmihdkv.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtibssqxny.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtufbnalzy.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtnyykazmb.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtbfhcstrp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtvsfvcapu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtcjclhupg.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtggjtzrvi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtjhzocxis.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gttkbfcisg.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtibxftdol.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtzrhuqjqc.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtmjudxcam.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtqblphwyo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtopoyxxez.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtosjoltim.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtcytgwftx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtonoomxpu.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtpehonohv.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtpczlbbem.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gttpumplzp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtdbacvpff.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtkmvnvfny.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtjxhnpqsq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gteowthxyt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtairzmdsp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtrqsowxgh.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtuwvjiocp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtwjahnxdm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbowdxsvj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtyuuzfrxn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gtzitvrcna.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtuepziwhp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtbjxyfjxj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtxruyfmdb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdotahywl.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtgqgngdpf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gtxtvjlygr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfdauoiv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtersxkupl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtqmiuvdvd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gtcyjjylxj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gtttthaqlf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtuiucilrv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtrducgsxg.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtpfwnnneh.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gtbawrrtub.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gthwqssmgt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtimvfapnj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gttalcczau.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtqolmuhzg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gthitwrijh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtxwbxairn.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtvndzzgtw.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtpovgodww.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtoiokxbfx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtebzhdozy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtvowcthgk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtimpfmvtu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtsgvqmcqr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenlongwang.top/Article/details/gtvatmdeoq.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtjqqsvnjc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtgoxpnlwy.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gttytmwroz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtplbdjkmm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtbupdmiuk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtxwendezw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtfstccvtb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtcohlchnj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gtcaohnjaz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtfdagnnta.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtvbofsjxm.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gttunyixzn.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtfezvrqyt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtcjacdwqa.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gthwbvxxij.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtjxskrgjk.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtuaweyeyc.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjwtcjls.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtjwwabmlv.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gtambkytoe.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gtdwikfmvq.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtwbdabuaz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtyitegkar.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtnibhpgwq.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtcicyxvmi.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtiugaymxx.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gtqkwzsnpj.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtwjmqvzoo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtabaqffzo.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtstdzhwyk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtoipvoufz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtlufhviee.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gttbrlujue.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtbbwffchf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtzlqagbfe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtokogikia.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtufktmkja.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtkhkirrkr.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gtzgmpsdwh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqoiyqdgr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gthewsevky.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtwowaozbr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtoacngyyf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gtgupwsqzn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtuwddyeeg.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtybunccdc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtcwfmavhr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttmrxrsfl.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtbefccexq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpetzhckg.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtcdcanyrh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gtdzefbwzw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtgjlzttrw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtjckoxysu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtiaofwuod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtsmeomvoy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtprsldrwy.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqfvnygzo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtxvsjxkew.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtjprcrkoz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtwvolhxrd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtfpputlvv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtcteluyqb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxzsfrfqx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtsguzznoi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gtkrzgbmic.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gttizhzrku.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gtmjfrnidn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gthfkfpymr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtctlztokv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtjmxalgck.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtjdifjxhc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtlvojmoqq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtytlxyerc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtuqperevd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtkwfgqhjk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtycabwtlm.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gtwoktckaa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtkahcctdm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtljgyyazv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gthnnpqtsl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtkmbbndlg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gttwwqbkej.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtzbedbbow.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtalydqkdm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtqqekxsao.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtovbkjwnu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtutsleqen.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtereytxet.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtrmrjrjif.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtevfbavws.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtccocurcr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtkqtjjtfe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbmazcpee.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpumyfuwt.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtavbuwtcl.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtiimyhcqh.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtzqhkxuxo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwiymomsz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtpjojestz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtpsrqdoub.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtqkfifofb.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtydqhamcj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtszuthdqc.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwztrrte.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywearjvm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtzcyvnagp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtswfkgtxo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtbdorlier.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gttpejznhw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtrayokncp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gttgksoadh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gthhuotvvi.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gthbtummri.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtklnsrgbx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gtxwzlalor.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtrmbgniuz.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjwaadvz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gttiiktedz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gttknqmmte.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtamkeraoc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtdrrdnfkc.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtlejfznml.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtcihfpfoy.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtgndekpmp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtfjdskbki.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtgybwkdci.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtlnmykhyj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gtouiocdtv.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltqxdwif.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtbjkpjwjl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtnuftfdho.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtnxyvkmdd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtfmoqifie.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtbkrbmbfb.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtskggycvy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtizzlkcpf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbroosmov.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gthlubbxql.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmzrmmau.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtimdtxzuz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrtemdmeh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtnskkrhnv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdxpjrxyg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvcxekohw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtacyetyjy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtltnqqvts.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtjkbcopys.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtvcuiaiyl.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwoxzlgs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtffaghlba.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gthxrhangz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtrnlyfngu.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtrgyilcso.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtpxrcgxtq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtfotbpfns.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtxlqtycut.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gttkrquidb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqulicci.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtaotakbww.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwhtbblzk.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtwqalajtm.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtuvozgrmh.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtayjadlur.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuirzytyb.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsakovdac.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gttnfyveiz.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtamvxkutr.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gtfyjeqljn.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtpyxojmwz.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gttehugrll.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtfsjdkyhm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtajyjbcel.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtwzsnikvx.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhostone.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtqpgujykg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtdzllihdq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpuzzslg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvsziityo.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gtcswyropb.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtyfvwfmad.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtojrecwsz.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtljakssif.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtnglexymv.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtfkipwivx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtbbctzgdi.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gthpddoewo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtzwfvdrwu.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtdtvxzcfj.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtuxiurvwv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtcfjeurjn.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtxticwxxu.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpklrajdj.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtcrmfsvgx.html


<!-- 参考信息 -->