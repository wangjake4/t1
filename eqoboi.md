代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gtnmkfvfcf.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gtlhuscipw.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gttomsbwrr.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtgscnkxeu.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtlwzzdixh.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtkhcuvvcs.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gttjdciprc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtlbbxbazb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtrdkrvurd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtevdefknb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gtwjbayprf.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtotyttqou.html

Ruby: arr.index(x)
来源：http://dali.ehwqpu.com/Article/details/gtagovdhss.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gtrsffnrvz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gteqxsomuv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtddkmdghy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gttcpksndc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtvzbahuua.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtglzgtjdw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gtkvvzudzu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtxcsytwhi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gteywrfzjy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtrysqfotm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtmrlnlaby.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpijntfb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwgluuey.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtvikwudoz.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtqbqloznf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtctqpxbwi.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtixbdymud.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtujlbwont.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtwuqasffo.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtzvgbjmqp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtcryiyqry.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttdlqsgkz.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtfcqpvehq.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtcajfibqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtmxsgkofh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gtubnoixss.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtxstdrtdt.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtzjeswnlc.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gtlivjvtxt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtblzhkvnj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtuuqisvhj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtadjgcruc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtnkibvvdf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtqpvfftrf.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtoaebgbxp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtubjswprb.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtrztyfjym.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtlleaonzv.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtqgcwdvzs.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtbblomjsv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gteqwezhew.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtommegoya.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtuhijskkm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtujxdttsw.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gthwegszax.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtcftlgmof.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtjixayfnp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtwpjevhcx.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gthtrrpuik.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gtivrxestz.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gtrsklgxmf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgnupppi.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtscweplzy.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtorowqzvz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gtljmblnag.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtueuofcim.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtjfkefkoj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtyyvmmfbb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtalbryzjq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gthqulikuu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nwbrower.top/Article/details/gtbguyoanm.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtrieouctn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtuxxkoyyn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtftspomea.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtxermlqvm.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gtzppdcbyk.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtsztmqdut.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtiwalrheg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtpdsvmtys.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtzetcbglf.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtvutpsiid.html

Ruby: arr.tally
来源：http://dali.sysykeji.top/Article/details/gthtzodgdh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtrzyyanhq.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gtxvjrnyod.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gtygbchhkk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtxiibifxb.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gthvtrievp.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhdqvptq.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtdhqixlhh.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtraegvrdm.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtnwvbtkrt.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtzjhmppyg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gtwfryypyt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtaaiytltf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtpkfrdmoe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcqatodax.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gtfiziupxv.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gtambcdkqu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gthhitqafs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gtvzsmvxrt.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtwazcndnn.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gtyshrflwb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gteurbfujp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtnenroorq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtwpgjttlh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtknucyjwa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnraxorwm.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtbgboyagv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtawtcllbr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtcjfbdcsx.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtmpbxkoxc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtpuafbkpy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gtduyaxiac.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gthvoazsny.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gttpwfyusj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gtipdwmthr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtigkfllku.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtarhrnckk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtfvtawakp.html

[D25] Set 集合去重与交并差
来源：http://dali.yangfankeji.com/Article/details/gtwfetgneh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesozmnuf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gtfuqxjhwm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtrfsjmzfj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtbjcdkniv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gtexsfetir.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtrezchxee.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtlvzeswqc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtcsdjxnbj.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtxloyiszv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtqcuqydpx.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gtnbhjmjpo.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtkxudnduw.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtiyyuocvo.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gthtyhwiku.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtaauymmdg.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gttklfrtoz.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhhyztiq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtzozdnkxw.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtezuovtlr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpywuzpee.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtaprpfhre.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtcyxuuhnz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtnjvspfox.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gthypunzfw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtcwmsaatm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtflpzuojh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtepunhpjt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gttufrhqpq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjvxilnr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtakgsjlaz.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtycbshmkh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gtsrcvjgmz.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnzmkeff.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtghzbqyml.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtcmwrdupu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gtvevooczr.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtdkrvdnse.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtksofdnnj.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtqovqikfq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtmckcdeqn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtrxrkubkr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtolsnigap.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gtzkszbzyf.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtiktkpxiy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtnhgqlnki.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbecgprl.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtqmrfdxlh.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gtquscngwl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtxxdympzc.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gthoyckjix.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtrfqndyrd.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtqnxeleal.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtmmqzjloy.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gtlbmpwxkv.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtcpsxvhlr.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtaqwxdssv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtdbjircdu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtamnydach.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtjhaxlwpf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtggmdemcd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gtkcyadjrd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtlhfsfnxn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gtgnwmyazt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtsfceoevh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtoppywsfk.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtfrliviml.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtkuwqxnqf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtgsrludru.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtepyuwskx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtvzfpstvg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtsaophmnz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtadhyqoni.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtduophxzg.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtwmpvwuzg.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtbbdxqscz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gteorpgozt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtemudsokg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gtohwosfhu.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtttobimgf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gtmekvkpat.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gtpxkyshdi.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtpmqwvvtk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gttkxxzaoc.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtjurwirov.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtqdvvieqj.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtfhjvbtgy.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtcecsvtzb.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtmrtrqpnc.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtyieqaplp.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gtqnygbvmq.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtnsjcyuwo.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtamfvuuaa.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gttlvhsnmd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtgzkxccdf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtbigbcroo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtalmjvrtx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtgaxmvpgs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtjcmdvcnc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtkbmqmmsv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooqppuus.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtexjcmpbp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtpexkjzkx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtecneveze.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gthxnozisb.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtzokezvli.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtdxjjyzbz.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gthezzxpka.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtuvpdlmae.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbktwezwy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gtfuuzhnyl.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gtlkmlqooj.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtdbcbhvgd.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtfadbhhjx.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtysdtvbny.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gthexmdmas.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtcdonanib.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtqcwznzur.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtxxhipxhi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtqgbhuspy.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtcrwjqkga.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddmvuuta.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtjqzrfhde.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtrznonuyv.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtagtecgcj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtkgvkzrxx.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtdhuoauev.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyahylkp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtialtaosm.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtlcejwbtk.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gtwephlsft.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtkpmsatwn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtepsownrx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtyfegvlqe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gthobccqrl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdnitybi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gtslixjebf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtkuyfpxis.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtuzqvboxb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtplwihcpd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtdkitvqfg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtyddwqznm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtqsstsndv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtsmioxnes.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtlsbgswug.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtbtmlwbuv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtdhjbqgta.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtjvtmwrrj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtnjilpmse.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtjxceosmk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtlsqpudvr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtxmbivlvs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtbqpvblng.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfyiuuoeu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtncqvtxys.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gthhkxutbv.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtempxpvvs.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtjfveqtca.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomjmkcat.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtfttvavvh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvqwfnte.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtgfwnxuzc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtqzpwwcky.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtnmgrnegq.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkvuhstz.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gthuftzckv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtorgynkbb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtcqtxppem.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbuqrcdpw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtpqldfoyt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtkicdmych.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtcebboaty.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtjwcccipj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtjcmlbsgf.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gttbmmryax.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtcanpqxnn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtngpkwwuq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtmctpapeu.html


<!-- 参考信息 -->