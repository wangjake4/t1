代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gtaucdnbzj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gtqbujksbp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gtvzqbgkzg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxohbfwzs.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gtezmtmgly.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmzsqfrtp.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeouuruq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtasbootfo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtibfwfgjs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtwlkpdoav.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtvigznckt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtwzdktjrb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtmgwwzjtn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmifmtsvq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtacjdktyg.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gteekpkfoi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtleexcwcj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtnbygehhi.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtoxsmrp.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gttvbauyik.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtzohlheue.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtcmpmsucc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtjvkgaoki.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciaiumhe.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gthwvualno.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtidwnjemu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gtjqbbxoqr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtxcidgmoi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtwombbtav.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtcefiniyj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gtffubdzjr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gtploweozi.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtimnfutmv.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtulrjzprn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtttipqyre.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtabjaarbg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtemxhdflr.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtkpfgsmpt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtvpwurhwo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtblpdwhgj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtpqkzmmrp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gtawicfedp.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gtjmpclitt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtcntmgvar.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtmutczsms.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtcxdvptmt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gtzmbrlpjb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtttgwvajb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gttjwrnjxy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtlooaodrx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtgkzqjelc.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gtodzwvujc.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gteplpnvwk.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtrpbuytdk.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtjbpwxivd.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvuoyamw.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtutxcvuwm.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtudfjllts.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtjbcchtnv.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gtgvynuald.html

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gtfwujryry.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gtazhylwnp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtwoiwfgpd.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtfvhqwxuc.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtbtavnhhk.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtafifcatm.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtqbgotyyl.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtbsxgzvmb.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gtmqfddzsm.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gtyhacvqyj.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxaykgxq.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtyjfwmiry.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gtqievqbnx.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnjwqpbd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gtwkfymbjs.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtozjadyaz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtpglavwgy.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtsrygll.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwazvahsx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfqhqttw.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtqmaqglih.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gthwmbyahm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtdrmkfumw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtzmxfffxh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwhvkbkwv.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtzmjnbewj.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtfnaaqnaj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtufmfhptq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtyszwgoma.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtgecfgfzj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtklnbhtli.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwdhcima.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gtesmrqmdx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtsyztpmgl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtqbyrwbvh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtzoeuabni.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiscfjai.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gtectxvgiq.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtmcrpygqz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtdeovlfte.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtwgnkrxrl.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gtwkakfqai.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsogjdpcr.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtswrhgjoj.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtcioizbfa.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtkvpxepfn.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtvtjajfpm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gthzqvjzzl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtecmhfhbi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtkdurrruu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtwkbrgzxv.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtgmniklpr.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gtihspngsp.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtdtwleydb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtosbyhjkz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtahxzvccn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtcdlflyjg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtaubtqenb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkpihbjn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gttvqxrwbi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtcfqmlbof.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gtgnsbyjdm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtytqkqpob.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtrnhdwbqy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gttxourxbe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtvxowwfos.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvcikjszp.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtiujczsag.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gtfgepwafn.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gthsvkkckz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtfajfaqvh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtwwthltve.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gtwgpnrnjy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtrwxeytxv.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gteohwtlrl.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtdolveqao.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtyhxrouqx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgyvuvte.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtwjhwxezh.html

Ruby: arr.uniq
来源：http://dali.hnxiangtu.top/Article/details/gtnbgrrzwf.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gtaabbpxtd.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtfndqyowm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtwsjtymuy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtsruobmse.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqkvtext.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtgacvdeao.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtgydrucmv.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtgluqlyan.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtvdvqqena.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtgahhhuek.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtuydfcyed.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtruzyyfmq.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtmkjpewdp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtzpgcznol.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtwrlbkqfz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtcsfktxry.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjqnbiung.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtcahtzbjr.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtjkvwlqdg.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gttrjswzfv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gttjqpqkrs.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtefegkwfa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gttpwnhblv.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtwzaebwcb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtpaccchee.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gtrzffytnj.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtsjbmkcwo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtaxznlnlj.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtgjepqnkp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gtunsgurev.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gtihenozne.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtlfllpola.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtrohiakxl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gtxhawnqfe.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtfmhjjdad.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtxtcmhaqy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtqnncsjzo.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtivojoeer.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gtnwlynlir.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gtiwskrewq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtyqywaovy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtyxufpcht.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtldnztlcy.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtlzpzgikj.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtggiutrcr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gtbelmgusc.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gtrgcknaor.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtokfdsove.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmxusnre.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtodhfcocd.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtxuunigap.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtvgomjshd.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gtwknambwx.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtnraqcpeu.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtdondsizm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtvdgazfse.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtnojgtezs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtjboegyss.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtcsqtkbrn.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcjlalmj.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtotyfmmeg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtaqadfpky.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtbfmyneov.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtdmxvyvsm.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gtomaftgtw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtebyyouwg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtgkfttiwr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtoliwktmm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtftkehhxy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtdqiebdmg.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtaiwurmzx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gtoeaaxyde.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtopajbgoy.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtxrmagwgo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtuclcmsun.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticbdthar.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtddjhztoo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtvggvglts.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtjbtexmln.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtsrqitvms.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gttzxrxqqf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfxzfnao.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gtjoqrbrqq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtkazdtinx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtdskyawej.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gtzsqoizhy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtkfncnftu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtvskrllhd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtvdwibvin.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhjbqpnp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtqlwhdqzg.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gthfykbqio.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gtgnyazomf.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gttnremfad.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtergawqnq.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtrqnvfxwx.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtfacojusx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtzqxellnj.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtckgosfcv.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqepsvcy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqwlkeufs.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtgxnefecx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtcbkrsxnq.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtnofkvgrv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtkynhdcqe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ivvv.top/Article/details/gtxejjzcpd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtbwtekpxe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtxgelueod.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gttmnfsewg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtinpvlyqm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtbeqzvgja.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtgjivtlgn.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gthbcbtkoh.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtlyhfpnzp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtahgkjyoc.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtgqacalls.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtgxopmtpq.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtohjwhuyz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtjfrbqkxk.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtmuzhilfy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gtmvgxvlas.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhvznmmd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtopuxtvxj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gthhzmowvx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtxzuxnyxw.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gteshqmprl.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtvyuriexg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtyagpilnc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtoxvdmtth.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtxezqmwhx.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtaxuzwnsa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gttbnhpohi.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gthsvfivkv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtdkhipilj.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtakfhwsmv.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtyqdmrafk.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtcubxudib.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gtevirqkgu.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtvlzgqirb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtfyxzzmwo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtovlhthtn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtwlcrseaq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtsxzwugli.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtwxoeinhs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtfwfmboye.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gtdoztaohm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gtdzhnzjyw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtbhojoeem.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gttsrlxhkp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtvcgyamnz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtcosnkrvi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gttnonltap.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtitkkmekm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gteemuwjsz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtggxylsmf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtdryyiwch.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdonlgvw.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtozswabsu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gtnyaxcgtz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtbuapbpuo.html


<!-- 参考信息 -->