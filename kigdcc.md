代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2xfhtkqxn.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gt2vywujvlt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gt2sdtorvlo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gt2rgbzfrgg.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gt2feybxmlk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2prcrlfyp.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gt2lcjlkwdw.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gt2byuaytet.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gt2qodmlqsd.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2grbvgsyl.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2cqugdqtu.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2oyxilnir.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2wchagkbv.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2qmqzykld.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2fcusbtsu.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gt2lfwknbnj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2yxhjiekh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gt2xgpolozt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2tzivntsk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2iyuhqkrc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2kvajrggq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gt2rksqiqrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gt2efqyhimh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2xircyvxa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycalgpgd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2gdjyzvvc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hidhnsjp.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2unbpltsb.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzazuxtm.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2zcvprenv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2zpylxelz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2ybfbgajn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gt2pyeepbge.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2ydfkmtzj.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2smbsgxju.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2iireyybs.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2cjttdmux.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2owkmbgvy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gt2fnpdgtgw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2mkxypbbd.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gt2zkrptcje.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2qnrafhlw.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaqdbinu.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2kkmyvqee.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gt2jthiopzs.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2povbaqdq.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2npwnohye.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gt2yuijeukl.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2coszyahi.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2qikdeapq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.smart0.xyz/Article/details/gt2jpkxadgx.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2alkcmbuo.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gt2rzldfqxy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gt2vskwctgo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2zqhyloyi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2nyubcywp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2dwcscnyq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2pipmswqb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gt2rzbljxao.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2tariqlue.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2bahdsinz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gt2errtfdjl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gt2mdamyqaw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gt2vgquphrh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gt2jvweyzqb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2ypskbabu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gt2wsspcxcp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gt2vffkirto.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmpdmosh.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2obylaqim.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gt2tjuopnou.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcpqzdem.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqsavlku.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2pasvtgfz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gt2lirwtpss.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gt2tnwymkly.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcedzufv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2cqovjwda.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2njuglznr.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohpcjsts.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gt2wlqtqsqf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eivwtuxz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2kfnwtcno.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2tbhqczot.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gt2esbacmcc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2tdrhjzyn.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhpwnaep.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gt2mjsfbpzz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gt2tftgmikt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2aekrsjpg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2hwnahhpf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aplbngys.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gt2xdjfcspy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gt2pavzwzrf.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtwmhepr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2ktbtkglz.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2jmnzptmw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gt2akhuwaqk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gt2djgmuqys.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2hhpvpehb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2wigafdel.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2zlzmaizj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2ixsscpbm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2jndttkct.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2vwsyhqkg.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2moeeyccw.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gt2lwiznsgr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2ubdnfzas.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2sogpuydf.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2enwlczya.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oiocvnnw.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugnemfrw.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dozweigq.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gt2yxwbepus.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfjbxupi.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gt2jmfmfprv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gt2qcaxqjzk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gt2eyjdvdtx.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2loiukzez.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2vzqjzsdn.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gt2bxerovvs.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gt2kzabjhac.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qjqykaks.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2cnzziwvm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gt2znlfwffm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2ppayxbpf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2dkplygvd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2ghsithhx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezuribpz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gt2tbfewyym.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2vqboatbd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2acfvfpig.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gt2ezfmzqkt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gt2tuksvvwe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2nkggmpwj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2mtznlkuu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2dlzlzcqq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gt2xiimbcoy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2wmxxvhxl.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gt2mchdfett.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2kjzotjeh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rduptfxc.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gt2rhunxwwi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2eklmvtow.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gt2cycludmg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gt2vfvxqyzg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2yejmqpio.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gt2ghmxksii.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2fzpmpmov.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2nmvcdzey.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gt2veftmcyc.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2cxvbeipq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2fwlcgxhq.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gt2tvowqjyv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyacppwc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2wxjdkrzy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymtmmmbt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gt2ncccbzpa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swqlprcg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gt2jsxtdvvl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ievtomzy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gt2eyihfnvv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gt2xygbradq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnrvsdjk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2uwkodarz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2gonqbbbs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxynekol.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2vlisgaau.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gt2atuyqsxx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2vbewfomd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gt2qzuzdsqc.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gt2sevwzolo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwiyujqe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgundtli.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2xrjtszlg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwvrgfkp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2vchbffdb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2ysjoxkvg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gt2gcdnaexp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2shlfqklg.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gt2cfjmnprc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gt2zaeawggr.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2dykowars.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsrxstja.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2mvbkflpa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2eqfviirv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2vjdlcscr.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2dyjjbten.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2bfvxetau.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gt2uqdgzndz.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2mweqjgnt.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2hliogvvs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqpybopc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2kbkuujcq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnfgdupa.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2ygaksrgj.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2bxzwqymr.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2ibhttbyi.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gt2xazmbhgq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gt2roasozci.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gt2rccxuslc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2ktytgtfj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2tmlfhxyv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsxugjby.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gt2gxjouoyb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfzwwecd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gt2hvzirtfv.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gt2jtpaobpq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfcwgldg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghdpylfd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovphreff.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2fsproknp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2dxoxwbdg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qscbjcch.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xngltzmn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2mslgptof.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gt2ujsxfvvi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2yeysidnn.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvsjqswv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2ukwswfqe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2ifevkrez.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2qlqgqeto.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gt2maypufgs.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qqgmbmgv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2oruxdtxf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwbztybt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2hftkyveg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2yhqbkigd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2waxaewqq.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2hrwqfctb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2jrioktsd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2gacddcau.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2sgsmvhbw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyxhulnj.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gt2yjlsvhjv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2rqgwzfol.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2wuslivzq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2scgfcczj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2nkmjbypq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2addwebag.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2skqrvxwu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2eqnzfole.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gt2wdxtjwoi.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2trkworwd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvjhseau.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkoggcze.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gt2pqggaadk.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2khnjgano.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2qljfbqcf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2eqmbpaop.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gt2henbstvx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gt2xjllumlk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ezfdjywj.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gt2thhnysfz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2hrvgvvbr.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2oigmqwlm.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2cxxyqute.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ikrhwwey.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gt2jkbwdivt.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2oxeleqsb.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2dwaoxckt.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gt2wovcimxm.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2cirktwid.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2srhuuneu.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2fcespsjd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gt2gzsghppi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gt2ccvdidcg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsuqjyhl.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gt2sfglkteg.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ovimwkex.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2xlpsdzmx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2ctiklipx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bwwxrmgs.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gt2wylkjmqj.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2poonzvyx.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqmakxcg.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gt2ixyaazhk.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gt2kjhlfusm.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2jdhzuevi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2boyxvssq.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gt2kbjsfhhb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2ipwphtka.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qinpffzz.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfslamat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2occsulmb.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2aytxwrbb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tmcuvvvm.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rwnfxjqk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2rapjadqt.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gt2shwbkqis.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2thofidlw.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gt2gxnukhiy.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gt2gglwzala.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2sgxwjocj.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2igndcwwm.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anihaeoy.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2poahpayr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjbweash.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2byowbxow.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2opcaqutu.html


<!-- 参考信息 -->