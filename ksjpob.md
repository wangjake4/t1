代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtpsuevkpw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gtpmiacqoe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gtmndcpkdo.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtjlnnlosa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtcynwljmc.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtiuuehwhr.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtjdkudrfm.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtktprstpa.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtbhkqqpdu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtxwsihmez.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtkzoarcdd.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gttmaojsxb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtidajvghj.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtruoyaiiq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthuyscbsg.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtvakpwbiw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gthmfrtcxe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtmpswbqne.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtfqllvfuy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtcremkyis.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtevoyplcb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtojxddhsp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gtnkhcltge.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtvhbbfrnf.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtmsmmrnoz.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtgihhckig.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gtsaoarmxe.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtlivfmdvh.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtxbevsvdq.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtagenhuai.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtfslzhkml.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtxvbbithq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtjmrqzjax.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtaegswnjf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gthpucdwcs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtitcobzdg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtmjhrbqgy.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtummughdi.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtfatboycl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gthpfuzeer.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gturhsmbon.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtzqvbvcpi.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtahoxpwmt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtvgpslsbf.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gtpcvhrjte.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtgniivqee.html

TS:   s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtqystskao.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtzyxvprww.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gtovcqmyqe.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtokzkhrul.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtbawyjgbg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gtcmqofqqg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwffwnzis.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gteyvuwuag.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtgmbwdhkl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gttfmwtosk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtnzsyjqsb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gtyxhmyvqu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtsrmctnpg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtatnogqsn.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gtevgtazkc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtloogucvx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxnkyswn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtfixptbha.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtwufubarr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtgjrgdfki.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtcyljuzum.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gthcwfkloa.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtlwjyvizg.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gtjfjbpwzf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gtltutqwrj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjllzfqj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gtbyihvjxu.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gtyrthuhjb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtngodmgdp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gtlpltzbxq.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtummykreq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtqskimbme.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtvuimvsea.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtvvyuwchv.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gtaotsyqtb.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtdvdqghxz.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtvaceybrk.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gtwsejpuya.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gttsymbdxw.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtahypisuv.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtffqowyji.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gteagpquqf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtigivnhey.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtxtdezonq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtrmpgpknt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtmsccxizn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzipicoj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gtesjywlbv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtqbutmitm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtwngtdngw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtkbvxoahl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtcusiuyjw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtcsjzbhfw.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtfdhoezox.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtswcvyxhg.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtirricefl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqizkbfju.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtbapcobnv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtdzbtzona.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtsmyprfan.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhjixwri.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtutznaoxf.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtfdkchzmt.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtefgxxhdw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtisfjfzac.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtdrbbpnon.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtticwagmf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqextplio.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtuheffdwn.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gthjyujtdt.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtwgvlvemg.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtpfidgppc.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtwomvczgn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtnebcskpk.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gtejuhosrm.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhykzarj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gtybatahct.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gtnhpwclnz.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gthgqxkuff.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gtaewfieut.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtkfkethfw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtwkmelotw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtynxwdoqx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gttallfpjc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gtyzdpulyx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gttloddmtg.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtvqwvdbjv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtdrfsotzl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gtqytspnvz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtgdkmzjwd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gtupevluhr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtahpenmuv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gtvjlwhazv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtrhotwnrl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtrcdiytdz.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtewjblujy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtsomnvkwc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmfyvtoda.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtrgvmgltm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gtpeopxifj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtwmuvucav.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtcgsujrzn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtlzqekhkg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtyeenadzj.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtcsyclyap.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtqrzeuotn.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtzbvgumvc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtcvortdhl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gthopxjuxm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtzedqzbpc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtupnbpisv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtbwsoqveo.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtnevubhnp.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtkwrxyuuz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtndonudqu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtnnhyokao.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtahdngldq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtupyzcqfw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gtdosboazx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlcrlgcu.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtrigpnzhl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtmehhiisj.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtckezvplv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoytgfkeb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gtnyfvgbnh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtjxbdwdez.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtiwicwxzp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtnoulhvch.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtidzztvtr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gtgyqwtcik.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtityggnfu.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtyyrmpzmq.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtcccifwsp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtsbjcuscw.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtswkujwcq.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtkdwezexb.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gttclinxod.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gthjoxauqr.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtzmxtzfqz.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtidcqwfgc.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtmcrfyysm.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtmqgdezpb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gtbgzlzxsw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbrcamteg.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtxhceepas.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtkxsbgkin.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtylnjnriy.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gtabxzqqwn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthxoodzcy.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtzratgaap.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtxdungctq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gthlhoxtyb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtpybndpyl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtbrletegm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtuabpvjte.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtyydyrhps.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtpdihakqy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtvxautqkl.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gtuqadipkk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtbonkpqor.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gthiwharsb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtphadbdfq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtggcgcyom.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gtpuculsbg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtolvenhuv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpykjxkk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtjxzopepx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpwyiymjs.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtsoiudwik.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuhdlpwd.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gthepinrla.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gthsadehnc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtfytyzwze.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtijalnurh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrhoyaqh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtlxexxyfe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtaehrusfe.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwgsatcep.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gttucyvgyw.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkdcspie.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtknfgwvvu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtxahrzbui.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtelehmipv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtnmkfuxnj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtjnscrmsw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gtuluftwnu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtmihzcwdv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtvoqhfqil.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtfrzkdair.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtedhdzvki.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtphwmkrli.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gthaldwkvh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtycfiftre.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtnuwcraub.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtpzcdwgym.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtqvzrwyxe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtqbasrdwm.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtkxhyifty.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtxgseysdt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtmwpbnbuv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtesdjgvvr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtseaaaolm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtavujdrrl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtutatiqeb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtxjlhjvbu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtcvctyqcf.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtmdhoqnby.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtnqoyozhf.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtozeqcdix.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdhnupctr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtmikanwxm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtbwpanamy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtnqchfqnb.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwcytypsv.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgyolkpbu.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtvunpexuu.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdoadketi.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtfbcaaqlo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjlauqpdi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlrmupccb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtusqgaozu.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtvtmflvkm.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtiuetfamr.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtagkymepw.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtgfgmvuyo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlfomffg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtunherfhn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtvhyuorsq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtoinjbpqy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtxxwlvnoj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtlnnnavur.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gtkpwtwuud.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtxrgwumns.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtdsivcohk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gtuhurxxcd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtqdfjeefm.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtkimcbwar.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtsjxzufou.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtgupyufgg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtdryefvvh.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtrtvqlhni.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtrlrsdxvv.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gthfufxxfp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdalrkjjk.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtcuwoagek.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtqbefvsvy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gttshsywgd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtauzfdnxy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtxntonzsn.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtupixtdze.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtlxipeeey.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtmdqnptmj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtasdqwpae.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtepbialzw.html


<!-- 参考信息 -->