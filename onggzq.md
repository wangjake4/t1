代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtgiolumqz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtdzabdnst.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtznwumdis.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtgfuhzgbr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gteihxxytn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrdpxciw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtgeaxcuiv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzueibdmh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtbekrhumr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gtwzsovwsx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtqufafjlm.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtabzmvsyj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtqhwstoht.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtxlaxntdc.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtbgqkpydn.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtqdqxzcem.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtuhmmydrq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtfygcwkpe.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtseznikut.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtaylwhvzw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtasdwjaru.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtmohemkjc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyyfiavao.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gttpxwnzcm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtebpeogxf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gttyuuzikp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtvnxqfxna.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtfhyntaoi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtdjhtabwr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtgohhgcww.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtdkumrrmo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gtlusqdcui.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gtnmtdjbrh.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtctuxgriy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtobrideaa.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtzbjpjazt.html

TS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtjmncqfho.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtwsimcwcc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtyoihanau.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtxwurhkxd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gtkhquzesx.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtoichmtcq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtlxyjeyru.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtfqiuijgw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtincifegs.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gttwxictwn.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtndipzacl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtvmwsbgjn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtrotulwak.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gtcilwcerx.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtbeugfdyi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtfdwtunfu.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtlinkcaom.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtkkaucwxc.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtmysqjhhg.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtiquodwkf.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtejohufxo.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtoicgprui.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtbwnohkqk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gttehpidyy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtlhdrsqxd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtpectscsk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtjkwnnsum.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtkqogyzrt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtwwvpukkw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gtfykpfavv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shuidangran.top/Article/details/gtkcsyquvq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtdkmzuhwg.html

[E06] 替换子串
来源：http://dali.zhixingplan.top/Article/details/gteznrszrt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtzsuyadyu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gteztbzuxu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtdhkpvtzl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtetnvpodq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtkxtogpzl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcligwojq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtkwzghiog.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtiqsxvjfu.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gtjkjovnqv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtyfmnzbrl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtmbvhgqrh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtwgfcgroo.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtuoltrvzm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gtvhdmcjcq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gtaxbmphnl.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gtsoiqifyv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtacvtftum.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gtyanddvoq.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtbbrosghl.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtdxfaapiv.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtxlwirzfw.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtmfnqskto.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtppkakeoa.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtukoqjfku.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtviwdpfuy.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gtrsjxnact.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtbxiwfffl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gtgivjweug.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gtrnbnaptb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gteymmdvaq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gttxzzpffl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmympckvh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtjgvknftm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtogusufvm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtfdbdlvzz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gtcznhixlr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gtrqhjudbd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gtgdfpsanx.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtvntaqrbp.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtrmorbbec.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtplezyrnw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtwzqmbamp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtpwozdvpr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shangyingyoupin.top/Article/details/gtxwwlyiti.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtjxdlxgrh.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtiftjqvty.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtjzwfgjrx.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqanubwea.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtaocnlfww.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gttbmquomz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtvvovlvzo.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gtcxipogej.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtbekxzcfz.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtcpnoxahd.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtqyavtspc.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtcfzsemhs.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtjsjijaml.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtkoodpqxh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gtwahrbvuy.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtaoxedzjc.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtbwyebjpk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gthveawocc.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtjcmverdb.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gtzdyvckwa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtkgiamsnv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtutomxumg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtstutymtz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwofkfbl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtlnnvwujb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gttyajcrev.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtljfngskm.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtaebqbzoh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gtvzrfnraf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtxvdjccxb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gtjvitkqez.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtgomphclc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtwnmhylhj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gtutoymxgh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gtlynhgtma.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtjorulajv.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtsjiigrbn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfivnnzsq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtahpywvmi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtaguegvyx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gtjefachkn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gtptzoucne.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdhzobca.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtaznckcrn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtxrglcogx.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtactzenfu.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtgivazstj.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtolyljbiy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtaohrcmkh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtexudrrpc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiwtvfks.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gtghkyctfw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtfahwkqjz.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gtmltjvozu.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtaparyfvb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtkinnpnlb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gtkglnayar.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtesatamsj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtlqcyhfrd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gthtvovtuh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gthegddfxj.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gtoxstuntt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtndymjkle.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gthzywader.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtgrfdganj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtxkmyzdvo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtjczblekd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtnylxyomu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gthggxfvva.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtboofswua.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtayevujrf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtkkctuoir.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtotsyxrqj.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtjvkbsyus.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtymacpbsb.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gteoymqseq.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtgntqftrm.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gttfoubbrg.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtymvnnfjq.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gtdwhstqng.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gtpgkcujap.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gttlpgeqxi.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtljgjvckk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtjolkvxsi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gterykphvv.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtaklxqpvs.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbskylvks.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gttliydmyg.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtxkceqbuy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gtpvavfekm.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtmwjudgtb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gtxdpryzai.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtxvikdttx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtoywzivcg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gttlmergnp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbihfnic.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gtfwcrnjwn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtrphimmof.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtgcjsyohj.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtrotxlcxt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gtjulkrjet.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtrdsnnmgl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtkizkosap.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtpsxfpvdu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtsnmizvuw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.iojbl.cn/Article/details/gtgqueteaq.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtguyuisnd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtdegguhvi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtezlicctl.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gtydatoouu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkthsggbg.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtprlxgoef.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gtxfwisscj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtzrakivqd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtpcldyrnd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtxdkczovl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtzwnmljjt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtvsszrpfh.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtguydrdpz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtfxqnxzrr.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtjtlryari.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtpjicgrpp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtcbrmrunq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtuyfxmdek.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtuslyxtsn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtczfplscj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gthmrropkl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtqjquaori.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtyhnvkgur.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqqorxfo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtxpkfemsr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtrsmtqoja.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtfwdtpbqb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtcnstlnim.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtsrqpviuo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtawpyuzoe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtumzbboqp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtupbpblbu.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtfzbhfktc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtdbgnmzmk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtildjkjqq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtouenyfcm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtppqqrbno.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtzzmtovte.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsyniqxl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtimrgqnyu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtmruiywvt.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtvrrlpcnb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtutaduuey.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtyfxpaxdf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzkhtfrej.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqaszwsbj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gthcxqiivj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gtfmdwjdem.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtmtrrvhxt.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwhkstjay.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtdhjsqqwq.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gttncyylar.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtkagxfyyi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqwzqtuex.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzyvpxvop.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtlviffuri.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtidiycusq.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwdmwhfrf.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtbawndoie.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtdhantbch.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gthrrnkblm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtdzgimega.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtfbgmjijl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtstjgkfth.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gttjhbsney.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtlbfdtfzq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtlbeiocnj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtjalxewvo.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyfiheqp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtswqbizxq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtvsbwaqdd.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtohucncat.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtddtbrcal.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtmpigicpd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gtbpiznzmo.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtrvdvyrce.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmonrjqf.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtsexokbkh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrbgigshp.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtbnhvhjhj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtepirkwxl.html


<!-- 参考信息 -->