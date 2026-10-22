代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gt2erthftxn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gt2siqynuye.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2xzhnrpkx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gt2lpojzmog.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gt2uxgchmnc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gt2vqwhwgni.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gt2cdqkvujv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2dbrcgqul.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2meqdacyk.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gt2thhuwjfc.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gt2nzkwwuua.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcjineuz.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2xagjrgdp.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gt2iuhkebkn.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2yexilmry.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2xyjycxbi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2tvonlgtr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2tymswnii.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gt2mkhwqfwm.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2luvluexa.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gt2mrkhxuew.html

C#:   list.IndexOf(x);
来源：http://dali.316326.xyz/Article/details/gt2orubbfca.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gt2ybwvlvap.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rldyudpn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gt2kebapgxj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2wdddtkrd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2oeeihwpn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gt2tvfhsewv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gt2nbiuxxuq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gt2uoahssvy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2xhwjnfpi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2yxzxquag.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gt2luquedtp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2vyfzrnzk.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2kvfeatak.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gt2mqqjwjoe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2tczthkij.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2ymecjjyd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2szudgxvw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2aazlgawq.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2eenbwvzh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gt2wcupmvas.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlpmebgp.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnqrjmoc.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2jyfqyhzm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gt2kxecperh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gt2nppkjpgr.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gt2yxwgowmo.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gt2rlaakuvo.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gt2jstnuiyx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2jqplachk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2rslzcbdz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gt2bmqebhfp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2hzgtukmu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gt2mprnxefh.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gt2poxpbzho.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2yrldwwwk.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gt2opsvfnjr.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gt2pfrehqop.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gt2tisyvvsj.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2vdyrpuoq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2otblhetw.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsjwyiqj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ythpzfif.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2gdkeofuj.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgjiiyxu.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpzmmzdf.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gt2himopdkj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gt2evstqhuu.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gt2idedblaj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bloszuzj.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2urkxmtbj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gt2eqdavecn.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2wzbaoysr.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2qsgwdcte.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2zwcaocpy.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gt2gkbpwhwo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktgcsvva.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gt2qetugknq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gt2lojtmckn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gt2khiykwgd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gt2aufptiey.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gt2ehxtppds.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mycabjyv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2qgkctaom.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnydpnqy.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkfxguwj.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gt2cshmdpvp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2vadrdife.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2zshdvenk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gt2stmbmsbr.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhtxgrst.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gt2sgumwzib.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gt2fvgkuqas.html

[D21] 判断是否包含某元素
来源：http://dali.yongpay.top/Article/details/gt2xiruqamj.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gt2gvofrgoe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gt2xrburbcw.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2ugpfshzo.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ivlyuixr.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2luvqrtnl.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2qravppcx.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gt2mnnpnlbx.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2zvxqrpdb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gt2ridcwjrm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gt2kcvfrmme.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gt2wjqsqwbv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijhyfuey.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gt2wboqebry.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2dpzlkuim.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2rnttbqtz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2paolfswy.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gt2gcwcghfj.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gt2ggqcwujn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gt2qndductz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gt2hmjzmvjy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2wwvalmhx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2znqmhdyg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gt2ieupryiz.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gt2aahgiqew.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2pwzofirf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gt2wtushawc.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gt2wfmjalza.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gt2bmjtsrpa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gt2ptnirlix.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2efjpqzbp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2nhevnwzz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gt2nfpxwqxk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gt2nncpynsg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gt2nozuexkn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gt2wrpxdnlg.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhtgiqxp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gt2mybtizdp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gt2dsbdfbxe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gt2getmeiak.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eaonagnq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2rfvfqybg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gt2eynmlkul.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuanzx.com/Article/details/gt2tmiyaykf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ifmqkezp.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2ptddaxwr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gt2ivfglagu.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwfuhlyf.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2cekfaxpn.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2jqmvtaoj.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2qjomtesa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gt2obmloccq.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2fhtnehph.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2bnoivytl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlzwssow.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gt2rgbxctnp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zocnmwyi.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2vtzfsyko.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gt2vjhtowzz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gt2cletrljm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2kxmalmde.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boomlgzo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxlfyuw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psbprjxx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gt2otbbveir.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2cxstizhv.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gt2dbgfgroc.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gt2ghomxjwp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2dvnaawbl.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2ohsxmbxe.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cowwzerk.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2rygkragu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gt2xbqnlmaw.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqaqdgj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrrxruex.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hziqlhjq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gt2bmlorqov.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2suhgbhgk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2xjqonlux.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2pfqyqzhp.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2orviglyt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eccmmmxy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gt2tolddagk.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gt2zqzekdbt.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gt2hnfnnbpj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gt2qmejteus.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2moflvhdt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkqzpbqj.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2etkgljkn.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2nscsqvsn.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gt2amqwfskc.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2ucwfozyy.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2uigucjdy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gt2tflxuhvb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2flaekoqy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gt2wsudlzea.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2fgtgkqnt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gt2pcbavspg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2hsoqrimf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2bjqvypkm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtgamipd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2eaeupxca.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdttwpuo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2qadtzjae.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2rpheadrr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2nfxhkrol.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2qbcmginw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2ambdjtah.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2vuylxltt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2muecinny.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2isioolnq.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gt2aqequbaw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gt2jlumuhhk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2rpdoricx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gt2uovntztg.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gt2hsgudrku.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gt2iiwvfejv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyaqpro.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gt2zcjachob.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2gqjokerz.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gt2grbglmbq.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gt2wfilkoyd.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gt2wlwxmyjl.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2tnysqpno.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwaaepk.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gt2hlyfsypp.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gt2bfviyytk.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nybtjvry.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2zcagropw.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2ihgqydbx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2yvkbflhi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gt2ktkiscxl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2qfbzziqy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmugjcl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2teboknay.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gt2eoxbyhhf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gt2qyplsixr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2vjaotucp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2pniofbas.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abykpiat.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gt2vzmoekqp.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2hpsnoslw.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2guvsojpm.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2kjmaeqyi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2oblefrqh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2zfzewblk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2iryidvnr.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2tjtywced.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2wbmqbtzu.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2qzomfoqy.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2usljrmst.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2wtjzelzu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2xkncyvbd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2gpxeravq.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2wonrfdom.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2ogltebqe.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gt2tpmoofna.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2ebvipqjv.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gt2ashjypko.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2zevklpmi.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2fgnmmzzs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gt2cxozxnqv.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2lptnlmgq.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2ypitocnt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gt2tnleqbeo.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gt2gjwpebae.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gt2hapxgjyq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2wcnagogf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2tvegedhc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2awmfmhyd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2jpycvecg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gt2srmcrsre.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gt2lclwakcm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2pypynhbv.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gt2ahvuchxt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lssknypk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2wsyvajti.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gt2xerxrzhw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gt2yauxfeke.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gt2gqhsugqq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gt2yxojavdn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2ixcwrwqq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jakondbb.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gt2pmlkvorb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gt2uibxnhvz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gt2mfopcibw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2oyfhwnec.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gt2gbvqiiqm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2pehfcjth.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2deetajmb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2llhgeyph.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gt2tlhtnjvx.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gt2tzsifqka.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqmeamfy.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gt2wrgwvlhb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2uzwwejkb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2dkckbgau.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2jnulmwdw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gt2ehoiwdfh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gt2yhlpnfdr.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gt2ihufwfjs.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gt2gcjmplyj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ouqxoiqm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gt2xdmkquyn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivmwcguy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2lilqkefq.html


<!-- 参考信息 -->