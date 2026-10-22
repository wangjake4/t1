代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2ubacczat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2fqxmiwnr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2ttwcolsd.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2qjrtkhrq.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2lnynhxui.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gt2wsmseaeu.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gt2kvvkllio.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2hrfjmxig.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gt2cxgvlqul.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2lyyetmeu.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhdguoqc.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gt2ebtfhsun.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gt2pnzkaldv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gt2tjxrtlqa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2syqlmmss.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2bahyvxmb.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2dpasovkd.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2gdtpqwxc.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gt2iejvqhob.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gt2hjszpntr.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gt2gkevnvcf.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gt2mrkcfdql.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2rvbyfauh.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2blapbovr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gt2auhwssqq.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gt2wnmuykij.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2sjizrqgl.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gt2yhdncepx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gt2zzknqymm.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2rvztmkzh.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gt2aasiliwm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2nekezelq.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gt2rvpxsicw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gt2eypburvq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gt2thjlliuo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gt2cepvgikv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2jlzpyiou.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gt2wxszekzx.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gt2vbekmimm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gt2qpoghoyc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gt2anlecmcm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzzejemw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gt2rleuuxtl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2gbpmlitw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gt2ryeetzed.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gt2pasydczp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjsjivrv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gt2mktgfsdj.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gt2tlxunztd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gt2kfsmyyvw.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gt2axbrehjt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gt2edtvjilm.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyofufgr.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gt2hnpctzvd.html

Go:   slices.Reverse(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2vamkoifz.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cddqxerl.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gt2jrncdjvs.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gt2okxfnbxq.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gt2lxwbrhav.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gt2mdcrvyvu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2thajwlnz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zruhydmc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykmybbou.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmyjnucb.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gt2uaiczrub.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gt2lwpatcmk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gt2vzeenldc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2ckpndnmp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2qbjpehpq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2fbisbqzb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2mqckuutk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpfjrgvo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gt2puljyfea.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gt2wbomtznm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2ualobvgh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2iinaotsv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2hsewsiuw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ijscgnjn.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2nximlhvf.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2cpkgirdd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gt2jjuhqzki.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2dudcngwe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2zioodiih.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwfckcol.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gt2whriklkl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2azmapfqm.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2ezohybhh.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2wpdbaaei.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2ersvlkuu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2tcjpsonj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gt2vwmnkfxh.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gt2vlxuvsyc.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2zervfxcu.html

[D16] 求和与平均值
来源：http://dali.hysaishi.cn/Article/details/gt2czfqievc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2yvqdksoz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gt2ryfepbtc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2jlguvnnd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ybjtmlyk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gt2jxcxygzl.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gt2cqfhhoxk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gt2ekcsugmr.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gt2ejqxjofo.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2ndbrjgvc.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2drdvcyqs.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2acvepwql.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gt2gclffvwm.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gt2gobhbhkn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gt2tdzdtisv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gt2oxmdwzre.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gt2asmqwnkm.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gt2obpsuydi.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gt2klexuhqs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gt2oukhyvkn.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gt2lsourepu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gt2dgodlvud.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gt2fgetcooi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gt2ysnlleja.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2wzekhfss.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gt2wuihrttx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2azqsjzqd.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2jzrrepuz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gt2aocyotwd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gt2bwqqtari.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gt2awsmqzwv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2rwyshkzy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2kmlwqvaa.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gt2mzewbvvk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gt2oyazvbwg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gt2imucwxqx.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2wyausvzq.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gt2orihtuhb.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2jzsczvpa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gt2ucobujmr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2feecpefj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idzlsman.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2bduolxrr.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gt2qdlwilnm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gt2kqzpvqoi.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsdyypvm.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2phnanmtt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gt2pluhmepn.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2pffwxllw.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gt2qhwyktsi.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2zwcmfxea.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2adkzauma.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2wdsulzma.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2ebbcnear.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gt2ivdziwdg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gt2hgfmynwt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gt2pxtuyhvx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2cnmwtfsg.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gt2tyxzbuvt.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gt2yoccnfjn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2encuiwdb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gt2tzydsaqv.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gt2xiuwrymk.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2dfubykkf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gt2esvppegh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqyrvtyd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2ajzdfxgw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2pqbpehum.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gt2kfetsxio.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2yktcasrz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gt2rukqkbqv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gt2bisllvys.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gt2ovcmabjs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gt2fktvoyrw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2skqneomm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2xwrwrsdo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2jtlehymw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gt2bagvltdb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gt2wxaqputp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gt2biloichv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gt2mxmskeoj.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2paklgohu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtxvftjc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2fbqyjrho.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gt2xbgdpasm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhlayqyb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2wftawjlq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzyxxhh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gt2phqzcdxe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2oragtmha.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2ligdlrrg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2cnzbuojd.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2sealjbde.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2orofgrvw.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2pzrmvkoq.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2ymjhphzg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2cikeoyyo.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2mtdivybz.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2lihkjqif.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rqbtmiwr.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ocblqgrt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wwwyganl.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2qhziznso.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gt2rqajxmss.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gt2cglhvwzi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2voyluomg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2zahcabmo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gt2qchmxocy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gt2fldcvqsg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gt2vcpucojb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2nqczugql.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2yewfwbli.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2bdydvtrx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gt2mxxzenkz.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2ckeztlxc.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2cdbzbfap.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2sezmluyt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2kyimrnjk.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2hulqqfas.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gt2kjttbokr.html

[E03] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gt2otghtrcg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gt2ncdzinda.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2venwdaqd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2oahfoxsm.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hidosyms.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgzvlbtu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2giexqxga.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byaxifad.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2scdouuca.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gt2gusyytyy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2uwfshjco.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gt2jnzbggnr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gt2kyqhfqzn.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2jfazojbk.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjnwyjla.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gt2yosdwmxm.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2nprmtdax.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2hbfaysqe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gt2mlevcwgv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2dwczzjml.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gt2bqwnmyfa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2swlzqsqx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gt2uwhqwitp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2qhexjpaa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gt2zlvenris.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gt2whytwnnx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2ygehhmeq.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gt2zvxljybh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gt2djggngah.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gt2pydzzgql.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2xgahraae.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2wzuyczfs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2zhfkxjrw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbraztqy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2muorbysd.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2ueecdaan.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gt2gvsgeidm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gt2nktelwul.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2jckdcjab.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gt2yyrvvqxe.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gt2bzdmpcsl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gt2owihjoba.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aazykcok.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gt2fhskoxws.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gt2hgtasnsy.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gt2ewufplzo.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gt2nygfxcup.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxnyuxej.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2rdzindxx.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2edsuctwh.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2neoayeyp.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gt2nliwirgp.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2hxrtbdou.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bozcvvvf.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gt2gjkkvvqb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gt2fejtccfg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gt2hkhucmud.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2fetmvgnh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vizdeypv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2gzwacebo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2yzleuvlq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2doauhwja.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2bnysyhek.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2mmfiwagn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2pthmqyel.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gt2pweginmd.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2ftjbxgwk.html

TS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2osvbuhwh.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qumlimer.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2mnczvhvc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2voulklwl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gt2qxpmuova.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djkfvpou.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2yiyznkuu.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2unasidmc.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2gqaqygat.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdndbmoy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2alkgagux.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2wqywwmjs.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2qrgcustb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlzfkjlc.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gt2edytnlsu.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2dxwduoaz.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gt2lyhdfawp.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfoynobd.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2hkqnfbep.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gt2tkyurbld.html


<!-- 参考信息 -->