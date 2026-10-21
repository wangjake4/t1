代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gttnquszwo.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxwpwdhu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gttxygdgaa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtnmtxrxbj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtawnqmhdo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtcbiyqbsc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtrnwmpenj.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtzfdfqhpo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtehilnzhb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gteiwptmev.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtlwvxqhef.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtggsxsidb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gtzmiofwcx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtfxktpbth.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtdbibitdc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gtqlcxkrjb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtgagiyptp.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gtvkcvrccw.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtadtmxeov.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtxdlrrrvs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtrlgubjdp.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtysqkdukj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtuxpspsbn.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtthfgyifg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtezgeqekp.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtjdpashyi.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtdmkdbeng.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtqbgjxqzj.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtwemsevft.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtbrxfqbks.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gtqsfwcfxx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtmwckudxa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtmqrsdqrx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtqqcelxpg.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gttmdztacl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtjnqroiye.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtlrgellbw.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtteibnuvt.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtzfpqfxpj.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtuyufmihc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtjacnzdrs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtfgkzxijs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtxilpyknt.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsgsavuy.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtbtgdtivz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtkatvmnos.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gtyhmlnife.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtwkuhwlgd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtyfwyosss.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtljsfjudz.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtpurppxsk.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtxusrkifd.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtmccowevm.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvzzxuurd.html

C#:   list.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtyvgeeukf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtncewkwid.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtjymmxehr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhixingplan.top/Article/details/gtkmgnysbr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gticecqqgt.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtlxtpjywb.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gtmcybifho.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhrpjsuh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gtadxttwla.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtiupepxfa.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtqlelznnm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtywzhwpig.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtuetetyjv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlvowpun.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtjchwmmgt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhkymfry.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtgzwjliuj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtogveaenq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtktuaxkdb.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtsvdpvrxj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtuajemnco.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklfhxrju.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtzcjsjqxh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtosvmcukl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gttyiwkxoh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtuuthbamq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gtsstpucnl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtfrbogjys.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gtalzbknun.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gtfegpplnf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gtxcbanxvk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtgfbimxgh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gthnabiqkk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtumlewizi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtnemljeqt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtfrznkoll.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtwxvukvym.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtxntuphmn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtbqlmpofm.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtldhrioiw.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gthkcilhto.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtpfifpvcp.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtwmsxktqn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtnqvcmybl.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtfelvmekc.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtkqczozql.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcbkfaaqv.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gtopfonzjg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuucirtyv.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtsdvnegbu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtrlvsieea.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gtollfmppo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtlqhimweh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtuxmzyceu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtcgichkmw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gtyhnpgbii.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gtjpzvvpnj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gteevmxhcg.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqsnktyp.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtvbextqho.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqxtlurp.html

JS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtpspqdmtf.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtrdkypzep.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtgnoajqnb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gtoapqerkx.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtufuagync.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtvmjgswqy.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtlkpmxfgs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtrklocwzl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtkosstcgo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gttpkptffk.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtlcraiitr.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtqfcrspzw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtxyiktaqa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtulnsuotd.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtdwszkzbj.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtcewvvjmz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtzvbnruvt.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gtfgpzssik.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gtzvwnhhhm.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtpaugfzea.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtptbqrmyh.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gtvxndfhuy.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtsapcofkk.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtptjovtuh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gthrkmdzst.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gtswikaern.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtklqrqfmq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtioktpkki.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtnnzjhzml.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gttbiinkjs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtxfgthccb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtrrqbxosb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gthdparqya.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gtbqpahfry.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxauwsqto.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gtmrptsnte.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtynxelfjg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtpbauyylf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtpyhvomww.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtqalficgp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtgynffmxl.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gtdibzjblo.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtabhxkbch.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtszswydfl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtupcfzexl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtnnvdfxhq.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtdlcjixbl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gtqxktpwmv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtpxihnueq.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtrreqncsx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtnkchvfii.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtszfezgbm.html

Py:   ",".join(items)
来源：http://dali.yvedp.cn/Article/details/gtfeshpsth.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtadtorohx.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtqwbtilav.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtexjkhqiz.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtvztszxyy.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gtwrzkrmbp.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtxbkxujdq.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtjxvydycf.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gtuufnsdfs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtxbpybjbi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gttujymktk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjozzndx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtjozvtcct.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtksofvitj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtxcwvjgdw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgpbfynx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtmnxoyngx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtyidruwmn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtewugbjdv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdalswibk.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtilbflkxd.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtyipzcepu.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtnvsdfmqj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtjskeopzg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtmizcfcxd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gticrbrtom.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtfkdmztqt.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtuonrweyc.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtsoiiusia.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtisavtjhz.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtqwzuvsdd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gtjssfoycf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gteksftqls.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtouxtnvlb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtyrdlidza.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtvsmhfuts.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtgkxcclar.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtpheayzgs.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtzkngupdm.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtosvjeetm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtuaoqyovr.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gtdogczvtn.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtbxuzbwkr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsecmcqr.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtmuzcqfkj.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gtkebbggef.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gthqjyjwvb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtdoimoeqc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtzacvuklw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gtcebsmmpl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtqejnmpty.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gtxwvrznmi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gticwdpalm.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gteuvutrfp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gtxxwiricz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtkpvasrqu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gtszkgkdmp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtlssonvld.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtpagwhjvl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtndjetazo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysdqsnxg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gtyrezlodl.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqkhialf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gttojizxbt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtecnreldo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtnbysnomr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gteartowen.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtteiowcxb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtndsjqiyh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtpnxurcnh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtihrgleqw.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtsslpqifn.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gtuovgiput.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtnymkcshp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtlqroeuix.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclbowort.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtfxnaxogv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gttjzoiyyc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtxtxunahr.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gtoolgttuu.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtejzrcdek.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtfexqlgyr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtcorgbiis.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtmpsapefh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfozgqdb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtkmfsxsul.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtvhmflmqk.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtqloqcosz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtnmviuady.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gtzijcaeyf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gtwvuqcqcg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtnbcuyspo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtepytfnzi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtueijsatb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtoeazncpg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtpdplhgsm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtrpjhmmuw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gtdjleyptg.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtuwkqezyl.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gttcplvqod.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtkzodjcyn.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtgukugrfv.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtopkppmhz.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gtflclklig.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtnnekpwuf.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtseactjsl.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gtjslkosej.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtghxaqxqo.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtxyrapfpo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gtbkxkexyv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtdwnpaiwv.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtclidafca.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtlvinetib.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqywdbkx.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtqymnkknt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtxygkzgkp.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtghreovwi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtjakogwfr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtazzzstre.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtkfkyvsjw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtyccuoatw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtlslovmuz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtxmxbabhx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtljtfnqlm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtfpgupjjg.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtxmkqlmtg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtkywsjfss.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtwqjlkbmf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtasiolncd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtkogqbsmw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtgjzryqoc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtttjhqgqm.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gthgkrgleq.html


<!-- 参考信息 -->