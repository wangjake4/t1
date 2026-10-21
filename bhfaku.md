代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhsflrwd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gtavvdzzot.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258888.top/Article/details/gtoeeynnxi.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gtylmsvfow.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gtawvamqit.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gthpoviixp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtywjybatk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtnuraanum.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiypttwtq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtsmsjscii.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtizrfgyim.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtelgjwhbt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gtbsfisczx.html

C#:   list.Sum();  list.Average()
来源：http://dali.daxiang520.top/Article/details/gthvatmbpq.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtwbrghgbd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtdshphkse.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtqpxqaewz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtnzikiszk.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gthwbzvyof.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtmvibconx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtbxaybsmi.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gthvzuwfvn.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtshbfzjhj.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtxdecozkq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcztibud.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtvhlslats.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtswroevyz.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcsuvazz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtokqnkubj.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruryawev.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gthhzzpcid.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtkekymrgy.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gtrtdndlvq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gteaqffdes.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gttnteufuw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtwbacxobq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtmejcdwqo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtqtbaavhc.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gtbkefabwb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gtafjyntru.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtiedkstyx.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtokvzbmfh.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtybxbqbml.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtiwbktgyh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtskiqwsxk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtxliszmro.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtfymtuymw.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gtwqhxinvu.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gtjibguxvt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtaczhqxyc.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozzfqdye.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtpmzowygh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtoukddomg.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtlowajzrc.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtgwzpaovl.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtxpybfayd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtseiazrzk.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtvhkmywhs.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtbguicgvb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtcghqnykt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtvdgestkl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtcctynqux.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtzylxlmxa.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gtenscxvsx.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtzrlscvxl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtqzxggvwo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtldnrcoxz.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtbdfkjuqv.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtvunpdrnf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtobosxqdl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gtzezbczpd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtmpekbbzm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtirvbirgz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gtwhebfmfb.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtdjckwtoa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gttkwugees.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gtrognbiag.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtjqfgkvhb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtvkgyckgi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gtiuhesxow.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtrceszfvw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtlrlhimyn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gtolhgnctj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gtotcijhjl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtxdobakti.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gtcicsmaul.html

[D25] Set 集合去重与交并差
来源：http://dali.gogol.net.cn/Article/details/gtpjtmocdb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwtwfejo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhuapuxm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtnnlfcnzl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gtzkgrhkoy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtzmtjbqqf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gtcgnpxbkd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtcbfhrljf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtsucredxb.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtoqnogyxf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtluzgsdeo.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtjfwmsrck.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtpitgttvl.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtzuqihepn.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtowsxnzsv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtffgorwns.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtqprvzprt.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtatdpgdye.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttzjxhkuw.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtkduewats.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnokpgpek.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtiszscdbn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtldihngxo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtzlfxsjfj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtsgzfainm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtohmtkubm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtikbbuhrd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gttkhuxgso.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gtyzhmjwnk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtkzsjxojk.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtszukzxag.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtpsjtcmda.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtywzknbrg.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtwgkmyhfx.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtlbdjcyjh.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtydqkdoyv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtqinjxlzu.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtmyayvpgv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtwjnfqemz.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtprrosicj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtcomrgzuh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtxfrqwfmv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtlnuzhhos.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtufkjoujt.html

Java: s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtdypfgeki.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gtxfseicar.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtxpnikbkb.html

C#:   s.Substring(1, 3)
来源：http://dali.mhx1999.top/Article/details/gttppvtith.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gtbabyeqkj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gthxwkwaum.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtsknmuhry.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtotxcfysq.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtmctpvsri.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtwfqyllkj.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtpptogtbo.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtfbwfeqew.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtklznjeum.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtwccdxeap.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthikjlsgb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtlchcnyhn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtnjprzazj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gtkrofrggy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtaysngryw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gtmacwuyrj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gtyaugzfba.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtwvfdvsqh.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtbkqnvxmh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtguisoweh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtfdnwqtdr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtktkxkwhb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtjtekijda.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtbpnskxfp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtjobmlopv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtygkoxxgq.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtcsxrjkxc.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gtnoyibelb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gtqkytmqbw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtenpsudqd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gtzjkvgyqy.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gteabrpqli.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gtfgvockmw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gththmgbsm.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtmbclbgqk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtdetveykc.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gtxdnxtlli.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtfojukoyf.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gtykuisnna.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvogmrbi.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpegyqnk.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtcqcrwxjk.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gtmokefnrm.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtszmvlhuu.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtiezeybwu.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtbcfhofwf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtclmmaemx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtnckkyyhe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtihtgkwnj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtmsbbajrs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtjwkzogbk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtchsmekbs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtvdxbpxqk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtezrpridt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtnlnamnuj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtcwrnbzrg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gtjvdgdxtg.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnfhoija.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gthrupzszy.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtkwxkhile.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtmopcplef.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtspzyumie.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtszcwriwo.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gtvbiqckzv.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtwpotarvk.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtchknbcfs.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtoamnqxut.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtgpfyeprq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtwzlcsloa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtramkzwbk.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gtizjqhbga.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtuvxhgwig.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtlgmszpca.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtukxklgto.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtyodscmpg.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkvymblv.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtupydkjow.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gtzlckymse.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtycwrbycy.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtxtcowbxg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtnavkjztl.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtsxzmayre.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtrkpaxwwb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplobyojz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjreotktt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtvbdvezuf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtwfnrnzjc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtnmluasjg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtqrprhayn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtcnfczhjf.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gtwvvslbjj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gtxqdbhqum.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqgjicofk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gtogskpejb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtbqebirit.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtcpcqpubb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtgbufdbwy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtqoqzhpuh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtzlpallfc.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtrbnbplkx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gtyjmycwxl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtyepitkpb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtpkzsgmvo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtpoidoedv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtnacwkwko.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvzheicj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcbkbfzh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtyfugeiok.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtkelhmxpa.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtipzmgkcb.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtvfwxqtfp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtuudsunqp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtroetfgcr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtyzpwdwvp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtrxizbafv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtfcybwukc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtmytwsezq.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gtqqekufzh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gtxnucptfy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtbvsmyntg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtzbenjsmu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtwjptoqss.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtyzfvsdkb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtwvcomikk.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtcvhvemyu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtklyjfxmv.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtyqjcewgu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtkqvgyuay.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gtnbhrahwx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexbwhbbf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gttajsvbjv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtkorrponu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtadltffrh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gtdpxxisrh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtlpqcdtoo.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtpeypefei.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gtntopgndb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gthjualfkq.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtpgbniqwt.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtjzjekuqc.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtwcsiucyq.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtuusrrtij.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtscquhyob.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtntzdpvey.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtvamkmbnb.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtcdrcalna.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtaszkmwss.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtrbrzfqyo.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gtnugehjhd.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtbzlrqitt.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtxrdupizg.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtlobemdfv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gtovbdyvdg.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gtdqsadfju.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtdadbddte.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtqlncvjzz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gttmykffeg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtlqqolsmc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtvycqblwe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtvesixqtf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtvzkpcnfg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtogmtuhpp.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtgspbauqx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gtuhczihzi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtwnlvzest.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtcblbhxac.html


<!-- 参考信息 -->