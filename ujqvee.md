代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtqabpsjat.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtopjcqmik.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtqccntgdn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gtfsunqxyg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gtgzzgkjpa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkafliaik.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtguejghlz.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtshgkahqd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtzubiugrb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfvqpttw.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gttzaunrao.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiwxcypu.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtsavyahgd.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gtwcstjrsi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gtjxucpjow.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gtihimajzm.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gtwersbwws.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gtzdrpuapp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtelntxsxx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtlqckwsai.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtzcesemtp.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtbylacj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gthkotuoqm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtncmjregq.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtcdjkylis.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtpufjseff.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtitszsswj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtyhyhibzs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtwcigjqpi.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gtireqyslo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gtsuijbykf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gtpzdgwkkz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gtiyzehpud.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtusifswqi.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtigthqxmr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtwdkrpddk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtitmxlcan.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtyhjvafip.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gtvaififnl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cashguo.top/Article/details/gtagjvltog.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtpwehgxab.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtvnbtpebl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtbzgttche.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gtzacdkdaj.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtikponvte.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtmieilj.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtjzcgjred.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtlptildmt.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gtlfdjzxky.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gthpnkevti.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtdvohgxvc.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gtnerwekhj.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gttzgjdoub.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtazikatif.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtbholpwfs.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtrgbwpwip.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtkykxudth.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gtkonjzaij.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gttzmjafup.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtcjkycjuq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtaoyiyyru.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtsbqzfwpt.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtgrgagwxp.html

PHP:  array_merge($a, $b);
来源：http://dali.zycfv.cn/Article/details/gtmjwvmzkh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtbfpatnze.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtskaeellu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtduwskaye.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwywaravr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtwiydidtb.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gtpqgutmcl.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjxufrzv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtgdsdkicu.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtvwwsrjto.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gtjnzkbbrf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gtjqtwbuik.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gtkqbzzofq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzczzhpfy.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtndhrlmat.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gthpudnfqq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtfrrwqtyl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gthhoisqcg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtcelpimsp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtaecfqokj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtatfrnane.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gtrfaixonf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gtpnelgjmi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtimbzfrxz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gtreqwwsaw.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gttfetwjxo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gtdxsqkhnr.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtbgcreslq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtlqlctvio.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtwdgmfupg.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gtiukiouvc.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gteunnlvbc.html

Ruby: arr.reverse
来源：http://dali.xinyue.icu/Article/details/gtsrobzlvz.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtuwwwzttq.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gtgrmwczro.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtjydcweuw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtovdkfwue.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtxtedywyj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtktvuqaaw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gteisqeskm.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtxhndbdpw.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtbaugpfhq.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtwbfxeujw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gtmrtoxslg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtbstbfquu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtjjpvgchy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtrgtjptxn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtpznuojja.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtzpliyuyh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtrxtmqmfy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gtwhpoegkr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtlwqevddv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtcgevynio.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gttbqgqicp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtlthrluix.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtczcrkdnd.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtwkwjexws.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtrgivnkww.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtbfottzzx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtoosyjmyl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtfgrmoibe.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtvckpmhxg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtbbtwoszk.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtyfpqitdt.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtitcynaua.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtgnqkupcg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtctlrntad.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gteoetxarr.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtzctgudca.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtpunuqmcr.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtcvmekzga.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtcyjnkxfu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtsvlncikj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gthmyzrrvh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtnakbgwtt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gthayssdqm.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtkcmkeqve.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtkdwbcttm.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtlgkvwciy.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtgxikcttc.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtqavhibur.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtsgbruhga.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sxryk.cn/Article/details/gtzxuiuzwb.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtnugmgvuc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gtxamwlawg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmogvytgn.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtekeatbsw.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtiqophhbs.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtoracymgt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtvttjbmqz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtmsrxgcty.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gtgrjnjdct.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gteqxispki.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gthagbkhgp.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtdumqumuf.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gtgnxvndsl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gtpdlromse.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtxfsfngxd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gthqwpbhou.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtzdjkfujw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtltunvuxb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtdeewpjbm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtfgpxgygc.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtwqjxgowi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtkkaysktk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpontyka.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gthnbkvzuy.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtgizreemj.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtxbrwbcsz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtryyogtke.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtpggzvqko.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gthibfyazs.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gtpdmdwgzo.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtqwhwqgbl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtmyjcejhw.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtteoxfzdh.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtqijzvhql.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gtaqzrghhk.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtjlcmgxaw.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtpfkevqbw.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtkevzirib.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtrsaespjq.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtbgxovksv.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtfrirubni.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtniaexyaf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gtggdsxqdo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gttglamuel.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtanwyryux.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtcmjciuzi.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtrptwsjhk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtsexeas.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtievozqxf.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtoopbrdru.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtzrohtgej.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtopzgrang.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwlumoft.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtqjzecrqu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gthxmobmux.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gtltodcpnp.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtbvrdoudb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtxtdgwdlw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtohhadiym.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtzqaebaqv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gtdkvrkzvj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtewsnjvcl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtqfuqwgjd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gttgreosbi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtoetpwnii.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtulwdrcqk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtszxwbltq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtjakyrzkt.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzljgfkd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gtsbhgqdwq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtqpitamnv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fengsongda.top/Article/details/gtbkvrmwdw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtgazgpjxz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtpfqpssbc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtbbnwgesd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtrqlpbpiu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcyzghcs.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtppumcmbz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtalwbjemt.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtkvcbavdz.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gttkmfvxyw.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtboevxlfi.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluxhmcef.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtqsuapqzy.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtsieszvaz.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtmibnzpbz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthgmirqdb.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gtprtvwenw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzzwvsxcx.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtfvnukzqq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtsjwkvjjo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtegemzmqz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtnrpdpxil.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtuwqajuoq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtkffsngca.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtvfgoqthk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjxdviea.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtfkwojrvm.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtggzginrl.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbadmasb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jianghu66.top/Article/details/gtatzvhazc.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtzcioznqe.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtrdjgkiye.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtipsglzah.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtioeatdpg.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtvdsgownm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtvmiwavim.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gtpufvgxmh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtmwlvecdd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtjenoorfj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtjzqkryxl.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtjsxpxopv.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtmbjkdkus.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtcgrkgtea.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gturmknnxw.html

C#:   s.Substring(1, 3)
来源：http://dali.chenzaomai.com/Article/details/gtvblqgzwb.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtpzqvdqbc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtusggrjbp.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtqmwalnsk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gtrgpteueb.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gttzeypbxw.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtchcqvjuc.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtrbyxxuzj.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtsswlllem.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtrsmwkako.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtlnhvhxgc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtuxxzudzn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gtbmzrawoq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqvjjnsp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtdymyrmln.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtodslvojb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtmmdepjdm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwpzhlls.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtkvzftcte.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gtdawdizct.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtllhjiyit.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gteuevtacj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtdlatxkml.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtdsyjbzcp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtybmtzmdl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtzxrozyln.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gthsfclsri.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtehwauzqy.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmentsmjj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtmeyusuvy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtgqpawtgi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtexwogkza.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubzqzcwu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtfqcbvydu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gtyotwbyxt.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtukallmxh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtfmpktzwd.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gtcvwyyqrt.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtzuwjqump.html


<!-- 参考信息 -->