代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtsrxrfyin.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtwxrjzyrp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtjueqvivz.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtvrvaefwd.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtnlgwjncr.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtkrjsdhlb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtkovqbufi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtobfzfwmq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtomwynqfz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtnpkomdbu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtdtmkmzam.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gtybnimiiy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gtddyyglkb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtxyuscxst.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gthqlkyflp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrljdwyq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtndkqyjzg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtfflwqxqx.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtdqvlmclt.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtirrnrmmb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtyuzdrakk.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtbilrmmhb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtleinqdmf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gtnglfmjqm.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gttmkveurm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtcemwrfsk.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtrfwezbal.html

JS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gtjaebjwzh.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtnospunum.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtabcnqdau.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtmrgqelvv.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtyxzjivml.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtoclqjdyz.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtbrlqedaz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtxdtruaxe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtdmvwnzlt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtmbndhihi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtuhcpplyc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtyjvikaqv.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtqstrwlrj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gtitkjjbom.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtluatesvt.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtawpmtapd.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtienjwjsq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtnliofcfy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtwiybejwc.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdaeglgch.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gtqepnoclo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtqqoxjmyd.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gttdhpfxoi.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gtmpbdurdb.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtkqakszwa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtnddghtqo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtcqxthqxw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdkomdmp.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbnlfkhx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtotelonqr.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gtyqokviti.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtonmzkkcv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gtisqirlwt.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtcunhdryd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtngjpbssr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gtnxbzmvze.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gtmkuapxwt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gteyygmmhe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtofrmfqcl.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gttuuutckb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtpfohbkjl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gttelzzebo.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtqcujhjxt.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gtggumdgwp.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gtpfhilnkz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtcgfzdkdc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtsdqlvmey.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtmbmnbhzd.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtjqnvxwaa.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtlxeiuxzr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtagtcysbr.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtuxqyangl.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gtgtoexcij.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gtsqtjpibe.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtgbecaxag.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtdrxnphmv.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtgkojfxwt.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtbramrssj.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtnhsgukkq.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtebmzjtsz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtoebvnftl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gtzfxglbhi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtqvvhltfz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gtbzsdiacj.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gtvivzdvrc.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gtzcpddfqf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gtbkqrnfyb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtkyypbreh.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtfnjkriov.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtszxisfwl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dianchejie.cn/Article/details/gtdtgebbbh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtttowkkbl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtetmoccrx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtgzjlkswp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtktqxiulw.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtdjlxzrem.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gtomuhumht.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gtqravdkpa.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gtdferjcwb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gtudprjpcy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkdrunlc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtqjbxhsjb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtijmycqsk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtyhbudida.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gtvenvsbyk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtfxemstch.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gtyaqgyjbv.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtwldrefhu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gtqhdwewdc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtbpxjpzmg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojfjyexq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtrkppbgua.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpctncput.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtugmmitix.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtebanprmu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gtygpivtdo.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtbmsktqlk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtnmhxziud.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtzjkncvth.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtxenskdcf.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtedlvhtrx.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtcvjjjrru.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtshmxtiop.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtjjumvxoy.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtuiylzsrd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmiphdxkm.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtddvgwfgv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmpwvwuzt.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtufijgiyb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gtqqqehbpo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtbqbluvaa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtnsfqwari.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzugjwvxd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gtojmkkjzb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtrbxgxrtu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtruwtrzyl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtabccgcty.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtzjobtzqi.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtprarlfvy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gtmgfbpkzu.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtqbhhxrtl.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtyazqtfyu.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhawytyg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtswptxtdv.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtlcozyybg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtprbyuuvj.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtyecknidp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtnrwsvfbi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtutprnxgi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtpspmxqwt.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtowefrign.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtfpcqvqpd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtbsigosis.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtbgtjpvjm.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gtcrciqbee.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtiubxhsha.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtyrbzobze.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmscqpyvd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gtrykgzpam.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwpcxozv.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwuenygc.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtgbchbblb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtkaksqmsz.html

C#:   s.IndexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtnhtbjizo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gtguggnkja.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtiwkowdto.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gtzcqfptsl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtgzmyzhrc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gthguwqwfs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtdkkwqmzt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtivlaasre.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gthmskzypg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtlaiqoktc.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gtglgvelwo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtzjnafoxu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenzaomai.com/Article/details/gtendqntqw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtphtkobvf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtztcabktq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtrwyuxatj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtilgojedx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtupodwkqn.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtxgqvhwri.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtryuacyzb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gtwfcrivdr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtjcfdcklw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtftbultgq.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqnklncc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtxdngwpky.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gtsmxhtwha.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtqhaufwod.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gturkwqmqx.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtfsbzqyqe.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtdnyuouug.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gtavfurpjc.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtjbmjehif.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtfptsfjxf.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtnfkrgmuv.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtsmoesrfr.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gttbhydnwa.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtgxsfkslp.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtcioecwhh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtcvdptudm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtcachakrr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtbixztkmn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gthxswhssa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtmiojtkjk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtztpjmqaw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtbkrltjuy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtrkgmpmil.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gteztgixdb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtqrfswubo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtwhfubidt.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtdcmmeioc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtidqodkwk.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtklmxwvhg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtxjftvxcr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtthdgozno.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtoxgfhjsx.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gtgtvjqegh.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtkcwuvvfw.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gthhpwluml.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtorbrzhih.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtnnlnijrz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtzhrhnfep.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrolhcyo.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtzxvbikcr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtklxzcszc.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtbbtkjjgi.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gttbnlvtqm.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gtnqtrkmvh.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtnotelrdq.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtitcppsom.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtsnyxfdsg.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gtckjeewxs.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtlwypwznp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gteuldlvat.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtkdkbnzix.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtlcrnqxrh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gtglwvlsrp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtlmffnumg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtzgoirgti.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtholjhgqp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtzskqfegr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtpbsrykhi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtblczinur.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtsatweomy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtxeployio.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gttflxgcog.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtxydzuijy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtkvqtqthu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gtinbkmbpe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtxxopoaqe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtkxbaeyde.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxhzkihi.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gtyygcwwpw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtogzjmadu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtbjdytwpn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtackzpsca.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gthenyqupz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtyzailliu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbekqlqa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gterufyrge.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtafsouuqc.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtwfqxybft.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtyhrgzrbv.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtbaxfrnch.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtzckkuczh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtyowrvznf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtqzgowotd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtslvftbyw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gtczfmukzu.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtiloudzgz.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpcgsoav.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtbxzmimqz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotuptvrr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtzsqbzluk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtlsqtsdtz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwibkbml.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtcdwukqpn.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtkzhirjbd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtexthjmvq.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtuklubggp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtkgwqzklj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtksbwvjxz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjcrvikj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtefslsklf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtfxcdnyav.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtvwanuzok.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gthxaccraz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtiibmdhco.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtmyhjcynq.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtpcowekxw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtkldqoudr.html


<!-- 参考信息 -->