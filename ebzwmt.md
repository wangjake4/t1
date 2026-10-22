代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtsmrfqvuk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gttpruymcq.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtcnesdqbq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtqygstepu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtirgrwmur.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gtsmfzzkek.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtijvisnbt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtueiajony.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtqtwgnbkp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtnhtywray.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtctlglpbu.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtqorlbuxq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gtbxgienvq.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtrrgnglrb.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtrphekove.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtxqcqtebs.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwjscpnm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtqhvdwgmm.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtsqyikwzz.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtxtuhobxv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgqesisz.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtevkekdfe.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthldrzzov.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtjqeorvjs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gtrrsjyujf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtwxpptpcy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtejwvisya.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtidfrkcxi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtwxywchrj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtxmmymjrb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gtthzpexcd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtyjyaacsc.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gtahhfosob.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtkxbhsbci.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtywbcuubf.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gthnjqcpcf.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtnlmzbjvq.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtsjygbsmr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtyqjmdnnk.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtxpmwgcdr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtddaeobuh.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtjjgrwgku.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtoxiugwuj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtegviaeub.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtwrtjgfkj.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtjfuvhqbr.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtkfljzkom.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtzfgncupx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtkgmymgdz.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gtfzyfpuaz.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gticfkomnd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtgfhnchjd.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtnspqwahp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtfjyfrjlw.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtcbfoehvb.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtlwpuidkr.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtyspccydh.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtimxwzzoy.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtrgywxwri.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtfikjdvwv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gtawtnmoaq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtzfagpmdo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtiyoysrph.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtfjcepxar.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtlpmrevbp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gtaovqyvyk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gtaiucqngh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gtxqpvmozu.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkfuketh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtxxaovprx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gttpelplks.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtojbdoday.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtierkaafs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtiqhpknwr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtmqwltppa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtvuqbtddw.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtwyqgtgkg.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtsjyfeobl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtoyntwkra.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.316326.xyz/Article/details/gtoovezjdy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gtzcuqfwsy.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gturbkxuhp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtinsozagu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gtcbrdfxad.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtubxxeuds.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtmplsihjs.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtbjuzdroj.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gtucwdsytc.html

PHP:  implode(",", $items);
来源：http://dali.zycfv.cn/Article/details/gtxlmimyza.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzaffcxy.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtotsficuf.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtywruqaty.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtqhhfkoqx.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtycfxhzve.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtpwrsabfm.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtgyytjsft.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtwktizemc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gtqqxjnhpt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtjwxmngrw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtpemlqieb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gttcomrrtg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtzjqvlbqv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gttncmdnfp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtzacrcals.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gttiskzqzj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtyqglrqks.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtwgrumukm.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gthlqsuwgy.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtwigowsdq.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtsviopchl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqrqekww.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gttwlxmlpb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gtklgratyt.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtenpgqpjs.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkbgvfrg.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtrnveozid.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtrulghpod.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtoupawjky.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtgusmliqn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtprtgatwh.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtdmfidmkv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtxjtihswd.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtloocsdpu.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gthhxnzjdd.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtssujitan.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjincdei.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gthwzgpvxq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gthagihiaa.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtxpviwnhs.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtgtugssmm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtfxsqirps.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtlhcsfyjz.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtmlivwgoe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtwjcgosvq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtkhhawdla.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtbbkszzoj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtmtxpgvna.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtdipwzpou.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gttfzuuxbj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtkgbuaeau.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtrgzadnjq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gtibezwnfr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gtmhbmtwbo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtbnsasxga.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gtnzqarfwx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gtyubvjyot.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtykjfbsgx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtdxxpqsog.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtfklaxlps.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gteoknllyb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtfigysjfq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtkjpymdam.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtaetszfrc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtvbwjznmr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtjgbezexh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtryavtuqu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzsjzuxg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtflkfeqwk.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtriyxrjwq.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtmeatytfj.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtgwbjrkpz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtsiyoqpeh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtrmbxmvgq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtcyjiqoag.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtraqbbdeu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtugtotvzy.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtaczhafxr.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtxenbxvoq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gtzjtafzbk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gtvrvrbjpc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtxgptkung.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gttyxldhuy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtpqpfxplj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtqrhtjdet.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzlpnhmj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtcimnthbk.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtcnxgkrcz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtbzdevipn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtichfxhnt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpyawvsm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtdpmkbwxg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtvvdowzxs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtejkjgoob.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gttrgnxuqt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtsfeaxjap.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzsclkol.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtutorbuki.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtbrokcmah.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtecteyfhs.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtgjvklaue.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gtqkmemvjd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtygnbxbdq.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtaotlvrta.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gtnwrfgfxk.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gtwnsvqogq.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtvpvmqbyi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkpaggei.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtpvggknlz.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtdjdclblu.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtiwxkdnkf.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtnhiehrwx.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtwegpvvgy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gtczumxdha.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gtwpvkatsv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbeciqgk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtwbgaxqzm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtmbrisxwl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtfeylmkmm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtaktflnjb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gtqenwwiva.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtwmucqtct.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtgowyjodb.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtcxcedrrx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtqojgbnhk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtdijpgwks.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtalejotxh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtljtzpere.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgirxwvqo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtafaxjpsh.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtkuvvmjfr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtgfmilcoc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlqlmxqvr.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gtypivuceo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfblqdvhs.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtalwbrrqy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gttxcwojne.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtcvwcxzix.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtpwafztnk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtupnylcph.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtezdycnbo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtqvvkccgk.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtstwqpmjv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtbsijhhjw.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtdcdwwdvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gthejdyxii.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtldnzsnjm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtncfmfipg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukuvujve.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtdyseyxps.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtzfircidf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfqpcamw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtnwerqirf.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtexobvhkg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gtirxjmxir.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtlipzqigv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtenrxvecr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtbjdgxvgo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtywhiefkl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtpakaqzrs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtuqycinoy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtcwxbsgse.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gttwejatnw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtmjvrukuc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtlroxzcvv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrremmjl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtfsxaebig.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtnnircxdd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtjrxviiam.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtndyogpzq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtrdwvlgog.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtxflvcsjv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtewpbmb.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtsrnabewj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtxrpcsdtd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrzhtbvco.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtwlhpqrdk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gtarueivdg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxqnsdnng.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gthqqfykxw.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtcktotzjh.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrysminhx.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtapkpdhok.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gttgthidhm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gteaevzeoe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtdmswxrmf.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnfanqali.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtsxarsgqc.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtldgtmsyu.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtxhftoqfl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtvmrdbqdq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtbtbzozyj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gttlumwwuo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtmqyefzpm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtdnyzbyah.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynxhsgdr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtpfwwtzih.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtsegytgaj.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtxrnonbyj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gtvduswkkc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtssggidkr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtnifrcybj.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlxipwnu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gthnyvlole.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlbdxpln.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gtqnifuvyn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtwfbhpnhl.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtlrxxgcok.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtkaveoalg.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyzhlfov.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtpivzmaps.html


<!-- 参考信息 -->