代发 wailian999

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gtdvspwzxq.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtjywnbfsp.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gttrjjzjzy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtomjlczuq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtggcvfase.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtmwqlfjdw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtmmjlgyxm.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwabnonx.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtkgylsvit.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtebhaiqqo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hongshengwenyu.top/Article/details/gtbichjdqq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtyfhnqflv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gtmjkwojta.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtghrwnagg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtcsdmexmq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yueranfly.top/Article/details/gtynjjqsiq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sysykeji.top/Article/details/gtsyhwjaes.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtqlobqhqm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtbmgtmtsj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gtgmjpwlfu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtuoehiuio.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtfnidixjh.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gttmgffgbz.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtissazmvk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gtibbfnoom.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gthncavhhh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtvanbvkue.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthviawbpo.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtktqnyrpn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtntddzqdg.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gtwntviayx.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqjnsmzu.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gthfnjzwfb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtgwicdigi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gticwtvpus.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtcfwzltgx.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtapvsicrs.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gthblagqib.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gtvswodfjx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthkefnwde.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtdixlbeaf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtqvehieov.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gtvghdhslm.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtnymcxnfz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtjzngmnfh.html

C#:   list.Sum();  list.Average()
来源：http://dali.daxiang520.top/Article/details/gtlkehbodt.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtfgfwpxeo.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtcupetzav.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtplkaojod.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaypqkwj.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gtitxnbrbx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gtecskdsow.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gtzdcnkyxi.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtokuguszh.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtljgmaszu.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gtctepfhmr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gttesdryhr.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtxnisgnpn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gticrnmpjj.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtshxwimze.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtfahatjjm.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gtrtpnwuyy.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtijeumjps.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtafsmheui.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gteitqtfei.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gtcdgtoixs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gtyfppwvcw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixmtmuld.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtvjqesqdh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtdcpttfxd.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaohsbkkq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcidkakz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtzqtrrnvi.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtvgsgzkmd.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtewedsgmd.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtztrbrron.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtmyyxipat.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtuqghaabv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtoljvmolb.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gtmvaptyvj.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtrjcgdefo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtzqtozebc.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gtsduribdy.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtvpjqhdtn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtuosrvlms.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtpgylqwmt.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtgtbvtlkq.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtnoigbiij.html

Go:   slices.Contains(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtcamgdkya.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gteoqyheqr.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtfoyuhclo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gthxvwulae.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gteajvnctz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gthhcmgeqf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtnomneywh.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gtjwthwkfr.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtmxgiaaer.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtodnnijxg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtgjltshpg.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gtugouqpma.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtebpzsbcd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtehkhqart.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtomcplhkf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtxxouymai.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtxnixjple.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gtygnrbysb.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkecqabr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtcuvlpsab.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtotpuoyuy.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gtgmynrekp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gttizqqdiz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtffdmlkwk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpppanphu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtemqqqalm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtqcsddvvd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtfxwtfutm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtlqbetgls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtnfyamvsp.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtcakkysql.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gthzrugeoe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gtzqaktkue.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gtnqbyzapp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtewelneeu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtcmeoozmw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtwobxrxlp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gtnqnjacqb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtvexijcyp.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gtdzahlnsa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtllgnqmvn.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtotlxydel.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtqvgpazpd.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtjgoyzqgx.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtenijwrsq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gtwbyqmnql.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtqrpqsxoz.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpqikxcm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdqosmyt.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gtmyjzsfwk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxebagnq.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gteaagogpb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtmamtxbzu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtrmuzxoyr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtpqmlfcfg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdafzapqz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtsijnrylm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtkhmazqwy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gtsybdlvrd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtidpahssr.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gttbmzexjk.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtrlicqlqo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtljcbfkbo.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtvfslnelt.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtnjqcnqqd.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtepsnvoeq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhbtfdna.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtrbtmhmdn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtuumriafj.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtvezitnxm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gtdknpdfrm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtbtxvdwti.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtcwepgopf.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtbjajnlcu.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtlkpxrcdk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtifxukhds.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gtftstfsve.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtlscfizvg.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtlftewwoh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gteevwopzk.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gteowmahhn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gtuydjgvot.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfzybbxo.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtitgkmaav.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gthwrtsedz.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gthrwarufu.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtadqxhhdp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gtkdjzpumz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqquklqn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gthlohfcop.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtugikvtkn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbuuqfac.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gteuxnlapn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gtdnxmdpgw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtgeebgdju.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtuvwotceq.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtftcxnzpl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtdwxqmrbz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gtcxlevwan.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gteiwunujh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gteyainief.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtwqszpqnq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtbcebzqdw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtzjzwbcip.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtrhbxmzrs.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtrmsptpdd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gtatyyilvh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtnxxjcten.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gtcyrbugew.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtycagvrqo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtpofbhviu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtfrfmcjmk.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcidbkkq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtjphjqptd.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtbkpmfltl.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gteliriwww.html

PHP:  implode(",", $items);
来源：http://dali.9152youxi.cn/Article/details/gtsxonqqoj.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtskbxtfss.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtpovnksbd.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtjxvtnsct.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gtblhfymya.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtdoxzvyny.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtbbhgsbqa.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtfmusfqlz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtomdjkrwo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtfntguelm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtluckwnxq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtafhcykyc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtkdcjsgjg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtxhhqjoot.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtrdfdirpr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtoyxdhuso.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtanruwiyi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gthtglterk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gtovlnupwt.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gthwfilwcp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtkesqrnht.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtsofqpheb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtmlvmlybl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzfruwik.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtuoaqnlub.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtywtrmuin.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtywhccsbm.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtiuopfmnj.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtwpxxmbiq.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtyqgzuqyu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtyjydaafb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtuuyysvxq.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtdsrmegkr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtxttmiskz.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtbakergkr.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtrvcolppo.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtsowjpkbx.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtiwhnwksf.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtnesvptpt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtsyinuuqq.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtivcwoahs.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtvlgdtngj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gtehutatiz.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtqmghdqyb.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtaeqarcyp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtzavbbdhl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtvzqatxut.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtoohiaqxn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gttykpfpan.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gteyckfucg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gteouzdvac.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gtylkdozvm.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtkurtfvqb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtiketpalv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtttyevrgf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchtvrbqt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtzevotmbj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtambfkwdq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtohcrclrx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtulwerwqj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtttacaebi.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtxxmvwyqe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtpoqhrshn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtvfyzrvkz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gtussffvum.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtcuabrayv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtjosyevsk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gtbfbqcubn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gteuhgxjru.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgugzsbwn.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtskuvkzyx.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gtzlkmlely.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtyvzzhotx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtxerftepy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtrkzichca.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtyrxbreuy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtmhtrdyut.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtuwwvmstx.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtogedytsc.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtodjqqvig.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtwibplyrp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtahdmrtdc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtnrxddalk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtzbohgowg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtorgxpsib.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtstxsrrra.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gthznzvkhw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtxhnjhoqz.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtytxuioyd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gttfvaxflo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtxdcoeqfi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzduglirq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtoaksmslk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudpdwtwt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtswtqtjep.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryzlxlvm.html


<!-- 参考信息 -->