代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtdibhwaam.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtlodovfiu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtodlxxurx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtxokbezqz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtqooqvoio.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtgpxxfvek.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gtzayrhmve.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnotuqxji.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtsqtjanlh.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvlhnrse.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtzclekhvt.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzdzacrt.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtlfccyf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtzrjugxmr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gtuvnqgmbj.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtjgdkwtyv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtfcsqlmam.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtppntpypq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtmivxkvso.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvsfwdsh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtokmbqgwc.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtwyuowhuk.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtizfavhie.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtwvyakaxo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gtljoqmayn.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gtudahhjeq.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtbymackzw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtvifdqjgr.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtewemlkmz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gtvcvrzmqn.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtizvjbxkc.html

Java: s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtkbpvtzjn.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtxzxqafbe.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtmkmeiaqy.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtonqgnljr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtxwdcvkty.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtulukkcec.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gtproffcdc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtxzzzldog.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gtbicdsflj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtyixljium.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtunezkduz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtjnqzhokh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyobjbha.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzcncgie.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtiuwliwdw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gtpnwgtpky.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtzietuyyf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtzsizttsf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtqqfqatzm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtipueolkl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtbqfyehfw.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtvektfekj.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtcevghtxz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gttgjrykxr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkysaoghy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtgswuttad.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtpthyojcg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gtimfvbcli.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtljqngkae.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtohwkncth.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtamtwngjp.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsyjthac.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtfxlftjyr.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtkfidwluv.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtpbxqssbw.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtsfttftza.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtktdboyoy.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gthcfcmwmn.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtpwpturkx.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtqxmnpvgh.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtivykywkq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtivwhyeng.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnrfdbcs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynruwzwl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtdhtanfgg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtpyjpkmaq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gtymhbtxca.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtnegbaoye.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtyiomwxfm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtbnkacsdk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtjxslyqfs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gtxgtxzuzt.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtznmtojlx.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtrgtfptqs.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtrwfqmcjr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtvxwndcju.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgbgqwjq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gtgieegqkw.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtviyyiqxu.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gttpqdgyot.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtqmcnpjov.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtjebdzgjx.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtwfqfrbkj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtxmstiztc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtqclwvwfs.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gthlgdcgsg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtedclhumt.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtncnwvakz.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gthaosxczs.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gtwzwaguqv.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtazcqrfuq.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtbpycwovq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gthyckrtoa.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtxrqqiwxc.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtdzqsnztb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gtrguhfgus.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtccthpkdq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gtitmursvz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtblcsqjty.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtepczrgar.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtvqprkime.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtoyzdqgde.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gtijmwviua.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtprralhmo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gtegulvole.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtxcwrvqws.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtrdjwtubd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gtmbazckla.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gthfpbdjpe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtxhaidwet.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtmjubmtui.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gthfycxooo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gtsochcyxj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtxlggwcwz.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtjoxtzkpt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqlhdtvas.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtygxjhmkq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtkxhxpany.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtmpmcxsrf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtcpifssqd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtfsbmkjgc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvxawcpek.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtmbfjbjzu.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gttfwaiibz.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtiyccnwcl.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gttwqztbce.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtnchaqdeb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtvrdvhudk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtdyenkpkf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtqqkvbvdn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtvwalopjg.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtfhndmvec.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtupvpdjol.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gtzswgtbkd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtzfjjllmk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtysfbyxpe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtonapocio.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtujhyiflm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtxdxcqftd.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtbhhozvjm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtuhnknvde.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtaxgtlmex.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtgyiqupbo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtkgqzjwsd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtrghjetuc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gthavcevex.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtixekbnix.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtsccbheyq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gtbhceqdwc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gthxuqbvpj.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtoiystptr.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtdzjybyzh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtnirczmvo.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gteygncnji.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtshckclqz.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtpdigsbmi.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gtoqrmjzft.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gthunkhpvj.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gtifwdwysk.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtonqufhoq.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gtpqxvdbkl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtpgmkltaz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttkczreep.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtbfekdxnz.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtggqslocy.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtazfegsmu.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gttfuecwiq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gttucmhqkl.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtpffdxzvf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvhraqfa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtbyxxlfvd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtgfgjpffj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtokbrtijn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtuvuuzdeg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtkjcvahxi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtfzijbjoo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtmttdtudc.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtodanuokr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtpwvafbbp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtkzjqhvdk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknmtxmdu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtnvaighox.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtdotdeukc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjyvuura.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gtonhkrasw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gttmjrkxji.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgtlvpevi.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtjzzyhwlk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkejpnhvt.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrsjjiuy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtztqytpkq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gttablgcjo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtjwzrsomt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtegdbqxai.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhsvzwgv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gtpoikvqit.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbxsewvtg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtfrxrwujd.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwmvansh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtaprsbmmz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtduhnevjn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtbsbqvefg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtdszrszum.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtuklldcis.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcgbuwdo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gthrfpxyun.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtzzrgchli.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gtwmawuxvz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtpsxpdave.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtqxlkkitj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtcfpfdmkt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtvzribalq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtonfouozl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtvtazopez.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gtlcfxabtf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gthynnkgzq.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtiuatedwx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtqicmgxpg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtncnrmjni.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtofvadvkd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtmxyfwntk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtiycohgak.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtzdzftpwj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtjpexfrnh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtqjpctwyp.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtldyuuemd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtodnodobp.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtconqephn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtucgnykfv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbndzdbcr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtvsubymtj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtzsbkmsnr.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtziqglxat.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjobgkzgu.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtyvuviknd.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwscvzgfd.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtixhefdus.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtzmjfiotz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtxktsxswi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtcukpxdml.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtswcqxufe.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtfohoozcc.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtsxbfpefc.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykrkygww.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdnfbcvz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gtmwmzxssd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtxsusgyws.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtdlfqaqyo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtimtchlws.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcilzcztl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gtrclkfnfj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtfjeohjsm.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtogygbkjl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtkhwnjiot.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtabrimlzs.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtzgufvjir.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtxxsulrjv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtljwpoleo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtjumlvmxr.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gthwwaddxu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtgpwlvtpw.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gtjlvdacfi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtexagdhqd.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtvaugbbyh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtwjymveqg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtzowwbxtt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtincmkbvd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtrfyjwyvf.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtfpygwmss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtmydyauqu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhongyouzk.top/Article/details/gtvrhdsocn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjjwavpfs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtfuwunjxq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzsljspop.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxjphqnpf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtoacrasrr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnbmylggk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwbpnigkh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtizkbzvbf.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtmgukejsn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvbaadpto.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtaphbrokb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtsudyccmh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfwqtlbd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtjflaqeex.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtzofrpkuf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcovqnvou.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtaidmezks.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtocjwgccj.html


<!-- 参考信息 -->