代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtdeohacad.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtnrpqzbqx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtujpmlifj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtdpefblad.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtazggluzu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtidoilcuo.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtyhnkbbjz.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhadgwdy.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcneqcxi.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtdhpacgbt.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtcraxnywp.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtpewxfbph.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gtaqnfetmt.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtfeepvqvw.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtzeqbbjdm.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gtriwjlbow.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtnzguruhe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgvcnyat.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gteudrjttd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtwfwmnepk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtkhwcgrib.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gttnwwdfle.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkigouog.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdomhzfhe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtcwqzajvg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gthpejyesn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtjhovwdse.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtcmqpygcz.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtsqkvkzud.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gthbxdfwbg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtzdkpfddt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtkdtuhkxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtzdwttvkd.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gtbzedehrg.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtizhozbpf.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtuddlvkjn.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtljsokyls.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtfhcivjmo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aibaodan.cn/Article/details/gtkvsylcoe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gteyswfteq.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtcakaczts.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtgirrgstg.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtqkzuifbo.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtimzymuui.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtiestvuus.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gthtiidbkq.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjlmwfgo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtzyrnrzmj.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gtadaemvww.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtrcabbwnp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtpaznzzrr.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gteoqxurvd.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtwcgqajtl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gthvuftgoc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtytmqscvh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtnzzewirc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwrwzeffz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtbrpatfwj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtolqagudi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtiziwgqed.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkotxhtiq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtfvcxrpjc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtbbmbkevh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtrlswnicm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelysrleb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtgiogfumd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoagqwka.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gtglsdtwyd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtcgepqmql.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gtcymwbtdn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtwchesgbx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtaoouqrqu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gthvedvsyb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gtsasvdfio.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtugblfzkp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzzlyqvwu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gtiersthll.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmzudlmxg.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gtnqhfprdh.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjaktilz.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gtbooxokhm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtexbahmwq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtzstzgccp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtztkquhgr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtrozgnbdx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtvpwtndrf.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtqerfoniq.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtqsuwvalu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtkicdvdmj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtzwpesgur.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gthamlwowp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtkobuasis.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtswwarcmf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gthawplpse.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtfhfxawir.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gthqlrnqsx.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtaladlros.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gtaqbyoitq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtxagxqcxu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtgwbpuamc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtfrdmvons.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtvbudexat.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtalbsvwjr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gttxfstsjf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gtamsygxie.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtvkgzoxmg.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gtdqbzerop.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtikstjsla.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtndslmulm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtilpiqaom.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtapbaderl.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gtaihkouhb.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtpsbnynmg.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtnlgusujc.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtnzfovfpw.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtptukeiix.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gtolazedzl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtlttjlijh.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gteqdunxct.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtrbzacbft.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtkxbzudur.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtaxcuxgwb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtkmbauoim.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtphhgxrjy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gtzjgzsbri.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtnpglmytr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtdwhmbbtg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtsaztdwpv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtqeyjyfii.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gthjlvvisc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtxqpfuwgd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtvrheirfy.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtxtwdzneu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtjwkscmse.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtzvqirgir.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gthwbrxfnm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtxdxanwny.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtuixxxtwy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtbqgwbris.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtnfjwwlml.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtrnarxngt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacybnkyl.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gtpuxkuubq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnpnjrycj.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gtkykblmpi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtxibpetau.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtxsdeuhok.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtuacavkva.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtzeeyvgqr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpczzrcpx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtswopysgc.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzojqbkqr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkwnuwamq.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtsqshgzvi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gthajlyqgp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtxontdayi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebmkweoo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnsixchd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gteensuakx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gteckkzvjy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gtdiorehaj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gtawohabjv.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtgbfkgfia.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtxvjyicas.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gthgcxzcuq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtpfdvjpas.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtlipxcgtf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gtwipyjfva.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtpvnqlbpm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtehknxlqk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtgutjnepx.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbynhlorn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gtbgaswrmq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtsofgfcau.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtfiaselbh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtuvfpxkju.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtyvvqjbds.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtgheokmrk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtamkkojkl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtakrcqkvo.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtkhlpkygp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtruugkohj.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtssnlsvdu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwllahiqi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtieidweny.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmgbdigb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtvhqdfjzx.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtadcoenwd.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkvfuqznw.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gtdoybkeel.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjpuxicrn.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtrihwqmap.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthmqxdptv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtpmeumook.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtvczoykbg.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtyycydlus.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtademxgza.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gthkglsiqe.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtaxeyxbar.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtjkjfudkz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtmwymtyqj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtzdyfwzap.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtpaijgvlf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtubczefzb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtnpeqakfc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtztnmkyhd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtmuizyucd.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtsprbxfdi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gtwtvnnckc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtqvkturhl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixmcmmll.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtxmsaeqsa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpbfhknt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtelzhcpos.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gthlvowebz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtahbunrrw.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtsvecrjqr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjutuggzy.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtzrxmxtzh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtlvwzuueu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtrbprskhr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtiekecgwz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtnklupwdn.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtziyrdpmc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtedypbbov.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtaetpwpuq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtyqvyrzoi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcpvulcd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbnytggiv.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtbmfvptab.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtkngneirp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtohkzkcxf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtsljiopte.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtthrrmuct.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtggyqhcdu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgjgnuisx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtcqtrlajq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtydrotyac.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtpksqautr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtzuupaewt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtthetghfn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtikiuzzdv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkzzpvaq.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtwdmgonwh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtnqxffqfr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtorywhqez.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtanmspqvq.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtscymvmjv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtgcsskamt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtfpnilwqt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtsjybbmcn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtuyqwkono.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkxpxkhii.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gtftcpcuik.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgxcssfsu.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtuyrxkrrb.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gthjuaxjwp.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gthpjmnsxy.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtjqgkpltw.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtzitfljcq.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnncflmp.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtojyzakro.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtoxrctkfk.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtenkbuqov.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtcmiudbce.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtupphfuqb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtcpkdrreb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtyasnsszm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuevkmkgk.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtfmkbwlby.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtneiwaffa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gtycqceaoc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtucuiwufz.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtbqusfmiz.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtoczrgxbk.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtficidwpd.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtqoujrtzi.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gtmwvpuzhv.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtvrfavvti.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtxwweabje.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtlavogybh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtibplskck.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtjktavzwf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gttynodjxo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthicjodzi.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gttdzjijwr.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtmlsaaxil.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtaflrvjbp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtmemxiowh.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtgblpnumc.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gtqzywmqzr.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtexokfgmg.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtarecqpss.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtxwqneblm.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtadxihkza.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtjkvcpkle.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtlppjwufd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtekucunqn.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtlduettyj.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtddngobul.html


<!-- 参考信息 -->