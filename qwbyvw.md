代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtqgzceeoj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtntwcrmjt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gtewsatifg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtonglcsmf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gtcmfcetjx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gtusfjibdu.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtrhyvtynl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtbsanoudt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtzyfkwjnp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtlfvqtlje.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtrfcwhcue.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtgczobcjv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.kuanghao11.cn/Article/details/gtsyvqaevu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtvowizzwe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtuzdazuvw.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtvtczwwjf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtepsxxwlz.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtrizsddim.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtiulgbodq.html

TS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtzwpawori.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtkelrllsm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtrdmjqxsb.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtjazrwylw.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtdjfjhdvx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbolpqjiy.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtdnonlczt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlbdeyyde.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtmcuqfuqm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtorkizmlj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtzgmktqdi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtwihbcpmm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gteljvpkxz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtnthugnfs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gtufncmvnw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtuucvaumh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtqhwyyklq.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtivavkyku.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtzubwzxbj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtqqnockjy.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtykyyijab.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtrjhtwtaa.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtsdmxeoce.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gtwknhulfc.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtoosbfyie.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtnleipjge.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtdjejjzot.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtqedaerng.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtofikaxdl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtxlshvsko.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gthbrgtsxi.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtyheaewor.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtuoladbis.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtcdkpewjg.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtmpeqzalr.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtqyatsugy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtyslqkmka.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gtduczhmhn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtgkyxnpuv.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtaokvdnkd.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtzigcurhc.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtedrsbuan.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtobsxboes.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtcxzohqqm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gtobhixuef.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtuitdsoxs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtwlgwdnjk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtqvmixrzx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtdspqbyoq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtifxmyirp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gtcazsflaz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtpqnarekv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtwgcwgtsr.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtklbyeimz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtirdqtawz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gtljdiyica.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtalbsvryz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtsmkxixzr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtbafuhpyr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtpshfxgfo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtonrqmrue.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gttmstkdrj.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtadwtwitm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtnmpgghtm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtlyvvovmr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtbcanxzty.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtnsziylil.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gtgglbznnh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtqshtmyau.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gtvacokoaw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gtcpwdchul.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtizzowpqy.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gtkdgiwcmd.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtampybwyp.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtxsaesjfb.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtfybpszpv.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtchwfjncv.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gtlvwvnrkd.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtisbwlogs.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtzitwilaq.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtaeyfjyyo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gtozqbjoag.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmcvovbbf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtanygbgxy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtvzropizo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtvfttkrnl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gtnrctkdtg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtowugeszy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gteocjvgou.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gttconotoi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtupswwspp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtqohkmwwj.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtktccxhij.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtpwfxkdtx.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtgfzlxbme.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtykizzwyx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtgblbgqpe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtduptglby.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtomyoyxdg.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtenusmfox.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtuwygrofy.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gttfseyitj.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtsonpdzrx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyhijtwv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtjrnjusom.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtlvmlegak.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtligbeymv.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtrwcbpdhd.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtuedxbxbi.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtclrbpelb.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtuknlrzxy.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtbfyytulq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtazvefoyp.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gteuadzzso.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtiduqxmxz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtyrmrfabu.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gtxfsexlif.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gtngoqrcau.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtehvskfvf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtklxewvzh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtxwxxkpmx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtvvoghkue.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gtzqsifshu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtgmnsebsi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtlsohhmmz.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtijfazywa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtqldyqdlk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtrqtserrj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtoprslioa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtwzsaiera.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gtmajdadtd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtywxasssx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtjpjckltv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtzngxrmhx.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gthzydgdyj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtkaaonezc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtdohsopdg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtorkocwnu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtuqkjmacn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtyoxqceen.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtgdspbhhq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtdymratuj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gtdjqwtiow.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gtislfdqrb.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtrtihfbei.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtksmstejn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtcmqlnzup.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtfxkyaggn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gthkmcpxyn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtorowlhbw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtjfkufkhu.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gttfuqsuhl.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gtqykqmwod.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtvxvbbrgp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtlzixiitq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtkfllgugp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtzlyoaggu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gttsdxshkj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtfdvbcvgg.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtmlsyfvtg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gtgvynnskb.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtqxxnruis.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtgmgkvyfi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtigotpunp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtdtglgvtd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtdzcrteyv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtmitbeuva.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtclkirxls.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gtygamezcj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtabcwzmfc.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtylgfyqvv.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtezveuyac.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gtjogmeitm.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gthnrswbvg.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtsrpsxcfp.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtrezzbxyo.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtmonnpzsi.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtbappgxlp.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtukafigok.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gtekaeunhv.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtbwwkwtsq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtntijgtdr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqnlxgcel.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gtelomnuld.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtcpqcknoa.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtzhahqnav.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtqhupieul.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtlmdwsqdm.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtjndnmrig.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gthaytmsqs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtndbokhzq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtvbjaheab.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtpryuzudj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtfgiucrbn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gtcmbblxll.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfvqdgau.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtlluuejgy.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtkwrdqycv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtflcxpbxo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtlznlnnri.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtudwojopb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtaqiennbn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtrwevunpq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtautnlnoe.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gtifddracj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtiylncrcq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtywajheem.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtwomduufl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfqgrngtz.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gttjotnyuz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtfbywrciq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtdtlomazq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtowawhqek.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtrhflxzei.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtbofksbms.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtyjtzwgbp.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjpfydhdi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtsuhdqsew.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxusbeng.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtibcvyfsh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtpsfuunzt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtthhyiwxj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtddxwzvxv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtunogudha.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtbtmhlvgi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gtjhnbmxzn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtlgyyncge.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtesbdwgwo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtaloxeepk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtdrurwmnk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtmpsejxpr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtcqlameva.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtqyampcgf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowffjpto.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtbqpncsqr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtwknbcftn.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtitcfdzcu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtcectlixo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtaqccoytz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtinsobndq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtevmqyqfv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gtbgjkpwid.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtarbokxqs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtneakookm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtxgzwzykd.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtmmptzern.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtrqpcoztg.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtzigifrkf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnxlpiwmy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxaxlnywb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtpjttsabl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtfkxrqfbl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtrpfhtolo.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtdfcofcly.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gtupzfzqpj.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gttqqbaryr.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqwssnjq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpfwcmsvp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbuojxrmg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gthswkqcdi.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtozdgbwkg.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gthqdcabjw.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtpxtkwphy.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtjfcsxdzf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtgjslwuco.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtcjbaiwoa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcriywfin.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtpxitrkqs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gttkcvtekh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtpgybdfnx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjqlbgpn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtcimvyult.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtqdzmmfsg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtvkeuhhqa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtdwzfzlwi.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtbezcntlj.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtrpvufxcp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtravonxcc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtmgvkvetd.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtlnlplphf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtbcitzwcb.html


<!-- 参考信息 -->