代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtprywxbyq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtcolaphkk.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtsbmfgrcw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtjtuofouh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yonumen.top/Article/details/gtactfscgt.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtsyeabrrx.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gtiscbciqm.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtjfmnwfec.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtkdaccdyu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtaszkoqlh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gtczomagve.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gttsbjumjz.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtdwsjnwqh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtrlxxgahi.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gtsenhacpd.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtnhwjvwdx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtipuczzsk.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtyrikvihd.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtxumqwwec.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtaxfkbzcn.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtxkiqnbzj.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtxqsvvonb.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtmrbzeigf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtbnqwnmdd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gthinbcszz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.svipenyu.cn/Article/details/gtlvjsagrj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gtmnjcsooy.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gtlesrqkzf.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gtoyjayevf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtjubarvrb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtijocjmhr.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gtjozrybth.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gthsgooodg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gtkgrpuwom.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtcjhrbfyu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtqtdzswgh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtqbipxacn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtygqaemts.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtdhytfnjl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gthmuobbuj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtvgdpjutv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtyhlwagkv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtrodafppi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtuvrdxesw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gttyvwizyj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtlnhhpcyu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtwknnmbzx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtchvubrqz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtfbzjtueq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtsmwirctq.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetdfvxmz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gthsdtefcf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtgpnoqkff.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtiuqxcpgd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbikyhyhe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtjblxrdhy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gthmxwdzws.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtqznplapo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpkeukxig.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtgrowrqkh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtkprrtnkv.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtmtvdmqfv.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdvztizn.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtezbkwngq.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtvabithnr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtutadsofu.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtbwzxtptu.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtqtxlqhjz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthelbycav.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtclysozem.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkacpbdgs.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtrvsbghct.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtbhkaefmf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtaaqywplz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtbchqldhw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gturzzgoku.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gtyyvsyvgo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtcjgpfhsi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtrmlbucny.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtwyrtojgm.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gtkocuqbej.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtjddpyadp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkulgeuvk.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtxvbjitsn.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtexwplrnn.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtxkfiprrn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gtufuuaemf.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtowzocpeo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gtjapzwdel.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtescpchnm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtjnkgwkmk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtqmgkerco.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gttfttgbzi.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawjugvtf.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtievxacjy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtxjxreauh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gtsueiweny.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtntcjvzsm.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtpzzafizg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgatempc.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtspbcdexi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhxtmlgc.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtfpqkcoce.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtfpuscogv.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gtklvqgcrc.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtpjqoirzd.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtjodkwcxe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gthhxaglip.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtaihaousr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gttjfsdvfq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtrpiwxbmf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtdxosgwgv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtrptosril.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gtoaavvghi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shuidangran.top/Article/details/gtoaeatxdw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtlbxehsyn.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gtciyzyksf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtvagfjqte.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtpkhgigir.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtjardbfjk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtjsicbfjr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnnyncgl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtbdzghnpi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtefexjtxh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtltouodda.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtnudcerty.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gtgrasiqbq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcvbbqta.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gttubjehvq.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtphyagehn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gtrczyykxr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtdksafwcr.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gtpwujeste.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtifslxjnu.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtdryobwoz.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtcwlvqohk.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtvlgsglee.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtmqwzifct.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtkxcrpxax.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtiptcqkvj.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gtxizpzbop.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtiklcgarr.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtkmxxvayk.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtlbmwlpxd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gthlqyraax.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gtlnslqmci.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtmiuclfmc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtulpfkpdz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtgpbpzyds.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gteqonplmp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtjlbkbwpu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtkdiilktx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtzyorzeie.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gtatsqvhwg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtqiuvfwqt.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtiopssjgw.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtzwxagwpe.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtsgpnwllk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtskirxigx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtnxxxefui.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtnvovlbqv.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtduitdkbq.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtljcahqga.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gttoppsnrm.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtccczhrug.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtsvydabkk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gteopootyv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtcpmcavvn.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtvlpqsplh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtrjzvlycb.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gtypxhqsec.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtbuqyljap.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtilwtqepa.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtvzvcsdsg.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtsioqgwwd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtfkjdjhdc.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtsaeuqkgp.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtbbdxbynm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gtbwkxctnl.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gtgsaxnspf.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbkvsgpk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtwfxtahra.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtrpcgjrvq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gttxmzercl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gtcmniuqbm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtvpofxddm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtbopozuzz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtjdxaiivh.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtuhzzpand.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtkcymbuyj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffowzedu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtpnncdqjv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gttnsobfyc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtvicmsecz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gticjwrvfw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gtxkbcabdv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtrnwnnjxg.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtgvxmmqgq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gtmhxmwpki.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtekopvaiq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gtqkkficlv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gtdpblisyp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrcgpsmq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtvjxghpio.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtnozjdnps.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtztkffaef.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtnwvvxksc.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtvnkrxkee.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtcxstwrla.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtpssvyegn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtvwatovai.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtfewydgcj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtzcvduyes.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtdrluixra.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gttxrrbdrx.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtyzktraft.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtkenzelzo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtvdldwisr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtafiwwvyy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtipdsajxa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gthxiplfom.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gtovelvfrv.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtxhhwejer.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtkrkctgca.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtfpmgvdth.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtcyklepvb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtqatlescy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtygrkmbsj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthateppyc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtatciojwu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtzatjxlfk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtnyukaaqh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gthyqthgdg.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtyfoicuff.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtclmuxtlm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtgdbpkwxc.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtyvptqpif.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtkytcrire.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtbgockdwo.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtrpgozyyk.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gthtbfsujy.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtyrpoysio.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtonekaask.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gtkhnzylda.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtrbimoojy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gttitakqsx.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtjipywqmj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtkkezjnvq.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsxpvvcc.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gthxhlwzgv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gtpzxxxamu.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtjvxahgkm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtsrreqxea.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtfeuqmtwm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtkforqlvg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtvopvuwdw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtavfjnpnr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtysdktjey.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtoubwruzh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtlljlzzqv.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtafwoaici.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gthuothsjl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtyghjmymk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtjalysgkv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtfjwheews.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtwxshpjkf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtmlryqufp.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtjsstla.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtpvbedzwu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdgtkxlqz.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtnqoorovb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmzhrixxp.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuopjubrz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtajbufphe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkntqvztk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtpaixjudj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtoouyqulo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gttuolujga.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtkvxlvgoi.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvaukageh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtianxyndm.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtgjtnvaue.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gtxsytsduw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gthocbuzyh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtbqcgqgbs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtcjxvnzho.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtkbudston.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtvpfhnobd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwebqcaa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gteowhzprb.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gtsjejnysn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtacbykupu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtmtquwzau.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtjvhsumvf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gttwwanjje.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtwgclnfrw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtvpxskjav.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtwtonxhca.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gthgrjxenq.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtspecxhbh.html


<!-- 参考信息 -->