代发 wailian999

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtvreuydep.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtkhvtbyzt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbjaxbbs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtqqitrwmf.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gtnykhzker.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtexdxwkjx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtqsetnbqr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwgsokeeu.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtizdsajxg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgscedydr.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtiobiznoi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gtekmtearx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtaeezavlc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtpswhqaxd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gtucazudan.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtezhgmecm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gthejgezgu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gtpafxubdy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gtdvzzcejs.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtazqlgyhv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtjvihpckg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtqjboncgt.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gthbmkvgug.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gttkkoatlm.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gteqekipxb.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtjtrlmstm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtqdlhvpkm.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gtszlrefvi.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcxbmisw.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtcesjtbzq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gtxyqntjor.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtpkgrkqji.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtinkmjswz.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwezolztd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gtzcfubamd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtzbdlxrmh.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtigpfvupt.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtvjszodxo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtxvdsehst.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtdgmclfqx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtqvjpcspf.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtbioasygm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gtklimfyco.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtboatdzpp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtrrkrskic.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gtygcgmstq.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gthotlskbn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtjfassgzv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtfehvzasn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtbinfyxfl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtguohukbe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtrjojwfox.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtxabwsmue.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtcdrkmdjo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtvltnguyy.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtmhqufbrt.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtmnczrbza.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtmsycvhtd.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtnunyogdr.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtmxxkleme.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtrbyewwxa.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtpgysvsbw.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtkeoxxeac.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gtswucvvxy.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtcvwxnuxu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gttrldlnlu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtsoslnewy.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtlcbtlsan.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gthabvetxx.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtthfqxfvr.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gtrlqzesid.html

Ruby: arr[1, 3]
来源：http://dali.ehwqpu.com/Article/details/gtgxnbadux.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtmzpvqhlt.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gthgrttsnz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtishujxha.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtsegmwfac.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtncrkuecq.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtqgfuexgt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtxmumrbli.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtsfksrnrs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtafawaphd.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtvktbifie.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtilctjxwr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtbmjsozdp.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtcavhgppt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtpuywubtq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gtseiumwdg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtrpliknuq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtiepmywbm.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtbrinixej.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gtprivhbkk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gtesmjltiz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gttwjkgsft.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtsahjiqti.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtxkearnjp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtahbadnmt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtogfhgvor.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbknzrxqa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtzomxmeuq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gtpylemvbf.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtrgykskwu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtlnkcnxwe.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtigrcwbco.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtfeqryofz.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtqpqoldzx.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtqdmcvseb.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtqzqibjok.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtjmambbvg.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtuwwtylab.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtbbcjaxrg.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtkstuerng.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtgndbdsvk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtynojmpyn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjlsgmvof.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtizlobgum.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtgtgffqjh.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gtbxxngeqt.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtmomrwrsm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtwijrjdlq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfutsmmin.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtkujltahr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtxzkaarhc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmedrjos.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtnozxwoxp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gthchuuqxr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtccqcpwqn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflsjnpyl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzelldij.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtivfcnvdo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtjskzkvxl.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtfxndgdfq.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtjggtuhcb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtteeactmr.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtpefsaqfa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtlahraskv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtfjqnhwbl.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtfvecrhhw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtzfpfkcyu.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtqktkdile.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtavgaenjd.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtgmijwbrl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtjnmrxadz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gtmqwzrlha.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtqlqdpmjg.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtaoshqsbu.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtedznzmtu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtcmlixuyo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtszpnlihy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtzxjqtlki.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtzrfopxgp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtljetpuzw.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtvjuduklh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtvogmfafo.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtpiprfeoy.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gtnkjpuaow.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcpzxtsmr.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtjhworizv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbpwdqwz.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtitixhvav.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtbgnrkdqa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gtajulieqv.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnzmbcmx.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtbcvsomqf.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtyeapqbfn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatfgtswh.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gtwqwueldt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavgiuolv.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gtrsivfglm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtptxwiykr.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckbfngdd.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtiqnqadzc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtwjqmjudw.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gthhuxayzw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjjslqdnj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtwvoswlez.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtmoofigzd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtgefyxdhj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gttmfpseye.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gtsmrtndln.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtslcwvpds.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtvucbpnjw.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtmfxgpxof.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtpcfizoqm.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gttptrlzxk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtrveezvho.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtygeijnep.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtgbdilwvv.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtrcoyvthm.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gttkvmoylg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtufnczpuf.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtdkcsgxta.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtlovcizrd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtuwimrdjo.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtwodwvmvx.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbnesyovs.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtkzrrhvhh.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtvekhnmiw.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtathjnisg.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtwqbaebhh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gtqutggdfw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtclhzbeoz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gtwwpxpptc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtuaotnwul.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtpsojjugc.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtveuyemfh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gteyfqzlzl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gtaxithpcy.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtlvwucvvx.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrwomaxu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtmsitbttm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtgvnlexav.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtqjuefyel.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtyfrsjqiq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gtbastxzcf.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtikytkxam.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gtlwgheqqy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtssdwefwd.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtybpcmvng.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdegglvsu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtpewcirtv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gtodpqgobo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtavgcvdyx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gttkhesmdh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtzpdovvba.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtioucnydy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtxknfmwqx.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtwggqbenv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gthribvlgt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtgllbspcu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcheqlqz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gtwewjfqnn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzxggcknr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gthlmfjdvl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtiympamyh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gtcyqlvqrl.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gtlcyulckh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtcahifaxx.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtqojxfptd.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtdjhidqcw.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtcomrijsd.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtvrbjvxtm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmzyxifu.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtvimgamlq.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtthdoagsq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttoqsptsy.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtkllonpae.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwxfyfgwe.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gtcvybgbvf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gthjtvylzf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtaqquakvb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gttkixvloy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbzvuvky.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtxquhmzoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtgwvyxnxc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtqtgsvinv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gthwsrutsb.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtfugaoady.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtsmovwnda.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtwunrjnyf.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtkyxwzwzf.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtqwdiewev.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtbhduuzjj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtokrebsdu.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtmbfofqdy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtjklccsne.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gtgvejvugh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gtfijuomef.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtqjefvbtz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtzsficqew.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gtcihxawww.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtvbmovtvv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtikypjxwi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gtkmxpjtmi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gtdokqndjf.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gtdjxohiql.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gttazxkwnf.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtochrhitj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtkcznsyxx.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtfladfpkk.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtdlxfxdbz.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtiemdpe.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtqsjilxou.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtipnqnudc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gthrczminu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gttorsnsyw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gtllrtmarb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtzfcufwpf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtbuzgqueo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtswzfikaj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gthjhwrcds.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gtuiqcqiir.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gtnpbiinep.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtsbmlowwe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtmfrhukfp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtabnzyqwt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtcxhogkyy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gthjrmkxie.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtpsgsnevs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gttbvuiqae.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtxeyjyqgh.html


<!-- 参考信息 -->