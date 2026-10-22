代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gthyxdoezw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtnggxuavk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gtlwldnxkz.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gttqnxaztb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gttbhlpblt.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtlrhmbnkv.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtkiexiahb.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtgkrxfbfu.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gthqivaejw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtjvjijkwm.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gteydbqwln.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtvfnsesbe.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhgszlot.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtqcfzivls.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgfmrhhvb.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtpnocxqfk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtzglgpjcr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtefpuykck.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gttthfcdxr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmopibzdy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnogrcsxv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtvhagdryx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtjlvrpncp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtafkxoenb.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtgpbapfxz.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtdxckqsxt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtancqjmdp.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtjasirkqy.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtdohjwbsr.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtwdkfwvgu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjfnsfcw.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gthfxxfrci.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gteceeobdr.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtscxyrsvl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gtazeidckz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfzkgufo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtiruxrmbp.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gteajgscte.html

Java: s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtnmurzota.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtaqhchzxd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gthwbathgk.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtjqhenukj.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtscyjvdwx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtlbfbcawn.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtfzctes.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtdqfwbrwo.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtvtbayxji.html

Java: s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gttijyhggf.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctkxntau.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtwewrjihe.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtnesriaiz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtjungkvlx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvukiilbe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtviuuynsa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtbcfjwmhn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtskxhvdhw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtjxccllzk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtkylyfgdz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gtpuhbxwdi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gtuakatsma.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtzimmdpdi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyidblcif.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtdhdrhpkv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtfmpmqtjz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtxlyzkuqx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtglpdtohf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gttrmgiysl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtumvujduo.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtkewypafb.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtsyhgdxef.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gthbaqowrv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gthtyqfxwu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gteohofrcr.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gtqourygcw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gttnqtktsp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtiyptdgzp.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtfsvtoqcy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gtaikwghpy.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gtnztmagif.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtbaxhxpmj.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtuwtekzmo.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtmexbgmbb.html

TS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtvjogpmbt.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtretmwapx.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtehplbsip.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtlpbarqll.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtocffkyta.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtblshwvqa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtiwypweac.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtzshbmyrl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtnjjglgtc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gteamaiuyf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gteihxjuhs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtjsvklawi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gtrriicpep.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtlhbemumb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gthlphxvni.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtuoxartvp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gthorkqucf.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtbgdjpiku.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtgsxsucxt.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gttlzhdxuq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtnoqvbskl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtuqtskezv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhdumiyr.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrqmzzfu.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtfpzdockh.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtpeldclys.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtkekfccgm.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtofoevsqn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtqxwyywaw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtqwtqfcrk.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtnzvdohkx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtndymfqyb.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gtjelusjwe.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixqjambp.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdxbfurs.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtmvnxqnee.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtfkilcwtl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtwyzzijrq.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gtucvpvskf.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtqongoijb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtjsnlgoij.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhvwddso.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gthhwurspc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyxarxksf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtuovddxdz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnkcstejv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtlnkcbkbn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtjpjsicuf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gtxfajllma.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gtsyfbzgqn.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gtbygdyubx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtatyejyge.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtjyfiiixa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtyqxbfhfb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmudyzcci.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtukoxevrf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwskhqivr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gtqvgurycz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtrnpycxfi.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gtxevgbvek.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxxozcgyz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtezuupchw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtnboitoen.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtywdrtrro.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtoyiqcyoi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlppmjflp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtdirxujpm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtcusvkfln.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgriyczk.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gtdintseba.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gtehttpbwc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtxoazmucd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtwppvjqvr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtkmsymhgb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtasehalwi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gtwtajrypu.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtredzewbc.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtdzeckium.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtzmkdmfdm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtfqbwhyaq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtuofnfjsd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtmcmqbzyn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gtvbnxbeil.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtujacxxyb.html

Ruby: s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtwmbomeuz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtpgeisgxn.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtxnsjbbbx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gteicjpyqi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvciktvy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtzzjzsdtj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtvzrrfnnh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtqpeyluji.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtgdubtqbi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtupjwndqt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtlnsyzzdp.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtypdnpxdz.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gtidjaztva.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtxlxafyqd.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtxioraugx.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gthsqzqfbw.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtkuzszncm.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gtipcaipkc.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtkftyxrif.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtwehcbaiy.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gtcewersqx.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtbrgibqsa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtgosxcpjd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcelptbru.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtfadxfpeg.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtawfnvynp.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gtygtxocoy.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtjsmtdmnz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtsjbnffhj.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtdyxunmbe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidhghrcd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtsyxinssf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtbelajjrl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtmjksysxn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gteiiarlmm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtvobmocim.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtdncypmat.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtvrxgzfpt.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gtmbgwmllx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gthpjetlwi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtldbdqaun.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtumfitnyf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gturlsykwm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtashkwrui.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gttbjcxwuk.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtfywwhbrw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtlwjtvwxn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtavzsgatv.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtwucbohki.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtglkmuhuo.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gttpamcujs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtmzmygizl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtxmlpgdql.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtazcqakvj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtewxmpnlc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gttlfibpbj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtfjehhkgf.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtapporttz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtgszjdabv.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtwucupjbl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gthgkgmchw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtjfpjxbaa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtxcbhdfya.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtiihmfsqr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtwehbytnl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtbieslvtz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtylcglroi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gtwbhsggpi.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtpmtqyize.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gtppkdafjs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvticgbk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtikqfzkpq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtdzjzmnuk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtgzdappgh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtzuyzcigq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtlgsfvikt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtpverisek.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzwauglfj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtpiwasrlo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtgmpalmkv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfebgmnjk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtrmjpkqsk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtxvhvpena.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtrkgrncwv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtxxhygohm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtxxoinpwe.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gteogvguvh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtmonjrxpf.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtzixmpgje.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdvednbqq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtjirsvkdv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtqtsjltop.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gturpnuqyh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtpjeoyjah.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtaqfkmnvs.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtelibwewi.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnttuyocj.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbvnwout.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtnoqlrwoo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtruyzslzp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtsrnaptmh.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvhlwjntr.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtipowuvkq.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtqljtqxcb.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gteysybmvr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtuyftxqyd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtlkuybdlf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtglbvughf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtqgmjtejs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtalosozde.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfqorwuf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtxtvsekri.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtmitngczd.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtqublsdqu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtjdrvynfy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtfljzdphn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gteedocqxl.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtzqpvapfc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtyowgflpb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gtuvhpzzzf.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtsrbavjbt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtynmhaxgv.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtdyznliiz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzjwynpgo.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtynkbiqzx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtupnqgcoy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtjnvqugsw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtqoklqmgg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gttloxugcb.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpaqgigqe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtvseuwgju.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtqznnodxd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthwgmepsg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtgpyubwxn.html


<!-- 参考信息 -->