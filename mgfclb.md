代发 wailian999

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtmtwcgrev.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gtvzycfiuz.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsxugsnq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtvdfkjpbb.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gtpzxhqtvd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gthikcmmkc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtmajaqipv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtahyuokna.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gtdcttvrwd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtiwrtyuaz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gthlbvglyg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqjvuxjcr.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtmlhwuics.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzqklcvqa.html

[D01] 创建数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gtqsciilxz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gtxslekrlz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtzljnviuz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gtnrcufxeu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtfviieghc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckrjfmmh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zycfv.cn/Article/details/gtpxlmwbqh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtlyrqolyn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwbwqnnm.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gtcvumtmbd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtokkdwmnc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtewpkvbqu.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooutydyc.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtgitzwxxz.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gtnwsoxzra.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtqomjrjmt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtybvkfjhv.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtebggtaxi.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtvctxghiv.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gttuabzkzh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gtyrumbwil.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gtlyfkpfdw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtbeqezgig.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gthhndyzqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtiiopscar.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gtwpusurwp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgbcbmjuc.html

[D04] 删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtjhhswgmk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtqlelurhd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtrvmntnij.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtziuukvey.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtbnaguvum.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtsgdkrkwm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtbxtyzfkp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gtuhoxdcgb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjigsnyjw.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtiwojygxf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gttqhebmjf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtlicdhbvf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtoltlrzch.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tian-w.cn/Article/details/gtzepuhjum.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtuvvkhlgf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtsczawchu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtfnowuget.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtdmearvvs.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtlucamaql.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtfatrdyfj.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtyjyswtdb.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtzsuwqnml.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtgnvwhftr.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtuddhgdqt.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtfapmruqe.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gtltxgmoeu.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtcsocnoba.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtlnekeheh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtgosjiqzj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtfphuhhww.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtegltnueo.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtdabsdhhb.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtjlopkdta.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gthphjskpb.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtemchsoyr.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtsoxvtbjv.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzktyapu.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsbvirvz.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtonlawrlj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gtnwdjlsik.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gthsbnqxwh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtslmbtsam.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gttbfrvygu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtpxpzlwwt.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpuashnh.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtyzekjidt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtufxvstbg.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gttrxyshsa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gtlkfmvrdw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gtaipnuymp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gtaoredbmm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtggwrmlmm.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtoyewbfbu.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtkwjjxagw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtihthunga.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gtarhzurfy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtbtrcnkbk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtphsqsqny.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtgkbvsxaz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtfrfwhjhf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gtyhxmwfuo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gttdmzhvpr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyndxmzll.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtvpyncnfl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtevqsdauw.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtzeqxvwft.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtibdlcisu.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtjjzouprj.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gthbmgzumu.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtsizcivzt.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gthvekorgo.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtdufvnzeo.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtcsjyfikf.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtfptmwsjg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtguqjxcll.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxdeuosje.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtzjhdyqiw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtoocguslh.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtvmekoxct.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtgjsbhfeb.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtlgkknkzv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gteyehftpv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtwpqypbyb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtpbpukrfh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtliksqtnl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtunhftfbd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gthxvcslxw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtuvnfxvpc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gteudqazzn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtrjpbdixb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtjcekqeec.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtzllpszss.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtethvhgpu.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtemxcesdu.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtrqsupjid.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gtcazmqwzk.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtwyhdqwix.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtngmhhgpg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtywhcfuzj.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gttfllshqq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeychspx.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtesxxmdbj.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtyzyktmsx.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gttlzplsdv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gtccfjxbrp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtbjwvjtza.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtipyxhxfz.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtcrsthowp.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtrbfegvmd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtndmckorx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtnpptqdov.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtnkppgizy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtlmfmkufj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtmxjoihwy.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtlasdvkkt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtqfhramcc.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtxhqmcxsp.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtjzgennrl.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtreuatxsa.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtknyiycvg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gtviwbaztm.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtmpotwqsl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtklkycemx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtpximlsfw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdododpsg.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtbhilkudw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtsqejntvn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gtpqovxhjd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtnekkdcuf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gtawwczdtm.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtdmtdlkoy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtjruqmpwc.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gthsqsebck.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtufylyoaz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtpdbqvbys.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtmuywcvaz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gtltkpzqkb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtufzthyvd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gtsmswakar.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtwzapuwnn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtwcykucjh.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqjfdytc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gtecjpptak.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtvycexkix.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gtohrfrahw.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtcnkiteec.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtugsstuvp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtlwrdlkgz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtfxsorzhj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtmsgtumlw.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gttvuylxxk.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtaifhfacr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtrscplmpq.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtcyinmupf.html

Py:   x in arr
来源：http://dali.sufxvd.cn/Article/details/gtpjssyyfl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gttxwvhknq.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtqekvshgv.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtikyulgng.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gtljojzdui.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtcezbaqty.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gtzlwfuifn.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtxsltwdxu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gtzsezjjob.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtxddjelhv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtvvvgyeyw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwodkqqo.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtbhsnewpu.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gtzyaxznyo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtlqybcchf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtsjjjcdye.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtjmvwknnz.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtobceltqv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gtzvecqsvn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtebtlzpiq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtmlgrpkwi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtgdtyhcod.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gttmrljhcd.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtojuogzrk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtmyhkbkyc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gtwrkxuxoc.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtvyqnwdwe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtkkjaiymo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtderrmalw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtpsvcfgfs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtyngeuotp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtamafxhxp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtfpiuorrb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtvzvptwab.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gtwtkhxelc.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtkfbuahdj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtahmpvksq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtyvnoaibg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprcdnald.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtbuoattpf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtxgyuoqtr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gttevbxqbp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gtwgrrhxnl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtaaptoqbv.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtomjjcwhp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtgxijjhsa.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdovemrj.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtjelnarmp.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtmgxozetw.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtirmfyvum.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtcmvkbwph.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtqhskowry.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtuofiazaz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoiafdulj.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtfxlrjrja.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcygdypxm.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfknjgygi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtignatsvr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtbvydsswk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtlwjtddrn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtjcfiunrn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtsgvkscgr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gttgyxvdcs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtkdaaufgq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gttervhsex.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtvqykfnvn.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtulpjutrq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqchaymsd.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtvwflzwnk.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtrwwuwymo.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtozbozehm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtldmlfzuz.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gthsnggqwe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gtmwsaedmh.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtgernphuy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gtjudinbgt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtodcfeshc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtengstlyt.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtuqpsvewj.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtsapxltiy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtdfbrlnwd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gtryukdctj.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtetedjieb.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtwdmtnric.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtuhhzmiik.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtexbawlue.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtdrikrycq.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtovhofpwu.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gthwavkzze.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtohhgmmvx.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtnjeombwa.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtvrkrlbou.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gttlmkholf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtqaimzdkj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gtdlfndvbb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtxrgvnpoq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnguyuwy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtrfeoekje.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtbaibvnvr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtwjyqudpv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtlgxlzewx.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtoizceryk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtafapkqje.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtrkbzvjaf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtkhgnaeuo.html


<!-- 参考信息 -->