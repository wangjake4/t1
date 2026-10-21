代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtjotencvn.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtwirtednu.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtyuarmmuw.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtmpzvxyxi.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtfwcuqepb.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gttwmynqpc.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtaemoaenr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtkvyunvak.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtypttwdal.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gtycowvrax.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtkctealat.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtgqggczzw.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtddbxfirk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtcfohzvun.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtrkbwndtq.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtmfnlqztp.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtcwgzpqwg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtbistpnjv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gtumoqjoux.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtrkkzvlgh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtknqlqfin.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtlidghqjs.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppjyyeyb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gtrbhpdcgh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtpeifowwd.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbhjigca.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacplgsex.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gtiuvszupk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gthytdxmrz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtzzlgqbhd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gttfarfmbi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrulhvqxf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gttwugrmkt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gtrnbdqoaz.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtghosjoua.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkaduaoa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtawjjijed.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gtppcupnxc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gthwkjernd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtghkxxffg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtztnkveyd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gtijieovbn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtagfklmfc.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gtltdggrzm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtuodxhzcu.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtzquimzva.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gttreqpcjc.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyvfwghd.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtbysyqltf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.0kj1m.cn/Article/details/gtlqmzdgyx.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtxjrdhqzp.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtczmfokhk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxffsruji.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnssgups.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyikvohbo.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gttqakvirj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gtnbotfljv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtabdxpyum.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtmzwygmia.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtjashfjtk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtwstjuzcb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtfiwzgdai.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtozclmlvd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtgjrspilz.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtjzkkduwx.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtycqjcayb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gtkwzddnpb.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtultzjiau.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtasfdowuv.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruqzvqex.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gtvgaluyfc.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtzwrechwq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtcibfyyqb.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzywklbky.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtcnjhxnib.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtuhmsnadm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtqbcighuz.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpevagdt.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtchdaeaot.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtshjtmyye.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtrzfufksu.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtlmkmcfgd.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gtgtxxiaan.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtlurcuodf.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gtxjsnbjdg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtvqitvnlm.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtukyidjqu.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtdlptywcr.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtbvjsmzqc.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtgqecjemu.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gttrcbitjn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpldjpxjy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtcvrvhnxy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtjwdzpcge.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtsytzhpbx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtagbnahsm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtnvlkwuuy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtskmssvik.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtfvsihbna.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gtwdgrqmsu.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtoupypbjm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtaamtvmkl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gtycwnwjax.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtntnimknn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtkaftxobk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtdknlaxxz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtqmtvjhqs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtwzsekrxh.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtganirsob.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtdzijfcro.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gtpdsegand.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjedjzhhi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gtumtkmilp.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtvtcfrvec.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gtgidgfmen.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqojemavy.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtapuyivvb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtktbumhrc.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gthgojcqwk.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gtkiroravq.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtpjqwgrfk.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtbepdgtww.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gthrpqidlk.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzltspxf.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtunxhmafl.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtxaegzaob.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtvrqkvkit.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtfbcoizky.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtborrqosr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtirdvzynk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtzrvybcwl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtztrkxcmo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtagalxwxa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtamooxyao.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtnbacbbfe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtjsinoajy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gtesurakqa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvwbyvsw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtuefwqmge.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtfshbutmp.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtdolimbsc.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gttjrpuopk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtfowvoawu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbdodade.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtiqwzrwke.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gtmmevcwby.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtzlretbvi.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqncefjdu.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtdutdpqjh.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtdtawtepo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcepfezeg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gteliumebz.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtkwxiietk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtwqvqgwba.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gteitrfmqz.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtalodsmda.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtkkodxnrq.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtfjdvpcvh.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtfickzhmi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtfmlsnfij.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gthxhwxhji.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtrsvmpvur.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gtcmsvtmew.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtkfgftrvh.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gtcukoatby.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gtkfngvyqx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvdhqrbn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtkgufmgzv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gtubnkxqlv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gttbbioedw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgwexpwa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtaevethhp.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtrovrtpvy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtdqmdktzq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gtagnviioz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtiguefrme.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtaiqpncmi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gthoxaivsg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtpugcxfdk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gtdibhymij.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtrraridxu.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtcibyzxjf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtwwzhvmid.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gtwlpqtqto.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtvjciaarb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtktxivlnm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtkgltpiel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtuknjsywh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gtewukkzrh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtrbohiijx.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtescyzgyg.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtyhiibmvz.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtahratfnv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtjscgcrpp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtvtkfxwpw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtwzofivtm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtgokmdgbz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtameedcuf.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtrgwtwyqj.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtqgampgvu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtlkbxyeou.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtjznsdwov.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntecfjyn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtxrxzdfbk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gtuqhjuutk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gtpzybcnnm.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtogrwngdv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczaadxme.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtmntwauyr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtsnxptmgs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtqlecjclu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtprnbznxq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtwpzwvike.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtxcpakdur.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtzvmnqsov.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtgzkticxg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtubklqnyw.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtsqbhahrx.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gtcphenfho.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtcdtblnaj.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtcfpqdbgp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtymthclxb.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtewsxppzs.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtqjmkpahm.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtrfsmygfz.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtwxkszcum.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtnrcfifjl.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gtbilqoacg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtuwvicpkk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtmuyaqoyg.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjyxykmr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtmiaeirvk.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqvuzsggm.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvxxjgde.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjfixiouh.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gtlxklalub.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtdfvndiok.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gttcdfiywt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gteftleeqn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtbzkqebxe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtvyevdwtj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtreshueyn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtqgbjzqng.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtsprzfbsv.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyvdklxn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtfvdychar.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtkympkiyd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtylebkexh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtrdxzfxxf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gttjffgyuy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtnxsshstg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtvrhwhctb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqnlvctd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjocscplo.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gthmatzaov.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyucznftw.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtmfypsiki.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gthyktbikk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtncnurxun.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtpntxhaux.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtvjmhwbys.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtdtmrvbfa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtttrzvizd.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygphqcla.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtikaepztx.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtdcsucihh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gtahxpvcsq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqlgslqd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtccockktn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtunhnelch.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtujkasejf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtlqxbuynt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gttqwvlhrc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtiwlpjgvd.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtmmpwrphp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxfvchfv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtqcsflodc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtzmqngvly.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtefizacgm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtzzdfpmta.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gthpdzkvhy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtcornticr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtsjbahubv.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gtsqizjytz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtfbiqhoou.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtszokmjkr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtzavdhxmw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtgxuaazxr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbictyzkk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtoibhemlm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtvvzcoslq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtnvumxkvv.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gtkbnuxriv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtvalqohxb.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtujxnmunn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttlghaluq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjyjtcjmd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtxqmdhyvg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gtpexdtkgw.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtcetkxeti.html


<!-- 参考信息 -->