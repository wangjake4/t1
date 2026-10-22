代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gtddzcxmia.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gteyajbzmv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gtvnwlldks.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtznmsoczo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtgpdraycs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtqxmvmcvr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzytiamt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gteoanbzut.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtdingotlx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtaqobihsb.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtbyipithl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtbglhwwdx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gtqmhbktrg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gtmasndcep.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmzeeqsl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtygrlgpkr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yonumen.top/Article/details/gtfitxwhgo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gtfqfxfjrh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtansnyijk.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtihvuhyll.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtedcoiwyr.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtorwgdigh.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtgilmtuwg.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtkbbgmgwa.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtnxkyaowf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrgbtsej.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtjmopiuio.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtqnbpnjil.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthomunxiw.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtrvqnktyf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtubjszqey.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrthnkfsc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtlfgqqxol.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtnvaahape.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtoydvttsc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmzpwzmq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gttuyegxpb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtnghuftpk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gtaxphkuuj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gteaesgydb.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtaljyddim.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtoiqhofvr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytqehnqg.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtjvkupmgc.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtppsxizek.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtcygdejss.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gtwkhouxtu.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtrypveuxb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtppraegso.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtvcsyuhni.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gtjnngfxss.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtwqpurxpy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtcmsnqsmq.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtntctvslo.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtiesuxere.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtpbgzhupp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtuaibrgbt.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocbfeyvi.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtdererhow.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtfjkovgmz.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtqlqvdvxq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gtduynpftj.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtiqimnekq.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtcjupksyb.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtjcomkoxi.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtuoeoyesx.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtcgezvpav.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gtycyhypxa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtsphdyidx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gtpwccuxgm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtxlgjvldx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtzkwbbanc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtlrtsarar.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gtxfnjaobk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtkekklxun.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtgbfyfuea.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gtppjnznvz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtozqljdcv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtqxizztgb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtmqlpcxgp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtajvtpscp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtaqpdfige.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtrtvyygmy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtvdhhnzbd.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhawbilt.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gtkjlewbmn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjatpfdg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtonwqhott.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gtkwatjcmv.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtjkixgvse.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtigkxpojd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gtfdgtqvqe.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtjzcotdzs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayrrcmxn.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gtldutqnsy.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gtyhcvemjs.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtkwlcwmxf.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtizgbctnn.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtoexdihxt.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtdayaekjt.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtrnpqnbet.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtioifeaat.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gtpfzzpbdd.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtjqwdsggv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtboutgozj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gtisoknxtd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gttoacgsyn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpfrihpu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtbqnoeyyc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gtjnrtijxe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gtwukoggqq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gthbaorpax.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtjazczpwf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtxhnwnvzq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtlawrfbgs.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtufppkghp.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtsbdwfxba.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsstrhncy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtmiejubso.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuczgzrmk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghturxcf.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gtmlxghgse.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtrucmeypq.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtvxqvoanj.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtvjeymitg.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtohbrjrix.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtvrxjaxlt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gtpdpdlsnz.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtcznurcmf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtuekltjas.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtloxthmiw.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gttbsnqfkm.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtazivdqwu.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtvmxnsyps.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtvkwkftmi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtgnyarzxj.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gtipxdljqc.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtlojtlqpt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtaphrdhxl.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtpejsqrgp.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtmaikdqoz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gttfexzgoo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gteoojojfb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtkwbpdlas.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtfjtpfozq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtcpgiqznh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmzieqsz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtkooylkdo.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoniaqvm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gtiodpcgro.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesahuitr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtjvmxhujk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gttyhsdoyy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtjrigaccv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gtoyscnsuo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gthlxrkfkv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtfdinauki.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtcgdyifii.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtpzwafagp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtmhbjzusm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtdzrdgjdo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrujgljw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtjywuhulx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtilwfxgad.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtqezxbqhf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtwblljgsw.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtlkznwdxj.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gttenknyji.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtfcfacjsp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtjehoqiba.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtlocfqefn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtmudphgas.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtqjrmnikg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gtrlwailrb.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gtfqfxvzxr.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtuosvgclu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtqtksippq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtndqscxkd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gthabweian.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtmkflderv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gtmawcnjub.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtuarseira.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtchapjsgh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gthnflptur.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtuxhzrpgs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtfhzthgak.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtnnbiwyvs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtijtuwoef.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtawscbnhs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtuuezfroz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtarbsivwz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvcmwydc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtgsdbfyfq.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gtgkvbkfig.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtmpzfrgih.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtyvocdvht.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtlscpvnlf.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtdrthwhzr.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtvevysvmc.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtnedyhkbz.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtamwidebe.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gtnzkvzkav.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxmppdxd.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtihtrykos.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtehfxfjad.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtcujbdkzw.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtawwxikjy.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtbdnkcbuf.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gteqsuoayn.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gtqxceagyg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtwwtubqyp.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtdawdnczz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtbvmzugao.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtpxcbtgdf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtwweyosqd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtrinbciic.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtnwuybobn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtvbbfylrx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtrdwohywb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gthcaaugpq.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtfqdwjbwb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmrrttyar.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtphcofmkr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtxluyxfum.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtcflzyyxc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtpdnbisvc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtfqsbgrne.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gthjxhkwmy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtzhohoqwb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtytgocgcw.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtpnxdqoaf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuelyoyo.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtqajmddnb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtfhaxvhab.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtertxcdal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtbthyhego.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtqvtqwppl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtskttjjek.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtwaudhfxd.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtcuoscsip.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgugrgwbe.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtudkcosen.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtitrdbwlv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtcldgonne.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtktwybqdj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmuycbfng.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtejslgfnr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtsoattycl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtxlogrkgk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtiscrgpxg.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtkiumfnkc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtgvjckufr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtvwahnjlu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtjxntgifa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtjtwzzcvk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtgkxvkmvi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtxzbuspef.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtrsxmmxoi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gthfzxzbag.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gttodjfhkc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtpbmxobve.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtpgachkew.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtrobtudvt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtociwnnnj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtqvmphspa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gtboamhzsa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtekxiibnm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gtgcugkfjy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtoqqjohkj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gtdhpzrnio.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtirrxwasn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgixctybv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtwjkqdznm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtziibxefq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gtgxnfzgsq.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgotvocyo.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxciiwnzy.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtmrvhtkip.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtmdcmnccn.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtinmfeqdr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtkfqqpxel.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwczckxqk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gthfgqinlj.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtjhiocnnw.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjhzuxlpq.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gthhyxlupk.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtvowhxnjw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtzfuylqat.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtacgsvstt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqrsjkxa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtseotqpnm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtzlbdrypq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gttutcsbjn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gtqxrnzbqp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtchxoswwi.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtppxnemyu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gtgecrmoii.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtgdxpioli.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtqodhhvhq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtkigegvdh.html


<!-- 参考信息 -->