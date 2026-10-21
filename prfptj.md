代发 wailian999

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtcobuuatd.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gthptcyrbd.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtxbdoexrc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtghloaete.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gtmjmtmyis.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtwagsvars.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gtqjntmswk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtyjjyofxp.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtxdmasvxk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gttwsaeblf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtuoektmzq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtargnzmng.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtswpupzve.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnpuynqsc.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtbtsesdfv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gtelwpwdhg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtaolaopjm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtjgxhnbbz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtlrzbrweb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtsvofvzdx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gtpgmfaitw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtafwwelpi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtdssbewxe.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtqlzwuoxg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtebyyjwos.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gtwegxvxvo.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtjwxifqvf.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzeyalsk.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtssnhytge.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtooujfkdf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gtvppabenc.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gttmatgzve.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtybigrmor.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtenhbemku.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gthrszcgdu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtqbpjzskj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtzjkxsway.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtwwvpynad.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtoossdfyn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gtkogiyvdr.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtbllgslhn.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtfqjpthtg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjritjpxg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jyoumei.cn/Article/details/gtltqwkoem.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtkuckfltp.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gtlakrekmz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gtmoqsfzrk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtilxvsoxu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtkrrumrnm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlerngthy.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtcyabccir.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gteacqopgw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gttcclxcfr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtxznqjzsm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gtodnjtqsv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gtqhepasdq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtqzvqfwsu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtbuahxqxj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtoyrqsagk.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtoeidvtrc.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtottllhwt.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtuldtgkld.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtctwivtbf.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtmdrovfdc.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gtlyrzdkit.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtuoqnytne.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtccgbhvda.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthazctnl.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtrzfavpqm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtcvkevqyl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtjbvidvxa.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtpquvyjfw.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtxqvryhkm.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtagvnsgtb.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtfqtgvfhb.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtoyutdzdy.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtbcymebgn.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtfwdwnxkm.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtjuatuyaf.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtwknzhrhv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gtyypqaykm.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gthrbrqyiq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtjycqaevl.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtzrbcamta.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtupfpkcpz.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gttgxnmzgz.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtyhjolybu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtzwblftdc.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtholehbfb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtuzxpqwki.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtwhfzwjgq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtmobjidqr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrmxdxgb.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtoymuistk.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtnohvimsy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtrzbrpwqo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtvbfasuod.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtjmelbucs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtrprkzlsd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtrxdbtmbc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtqsubogdm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gteytdkajg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtarhkrsaj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtkgnpihbd.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gttyhjzhhq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gttkghvfck.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtixspmtkb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtalebcrac.html

TS:   [...arr].reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtuowcdvnd.html

Java: Collections.reverse(list);
来源：http://dali.vqdsnc.cn/Article/details/gtmkjmhqto.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtuailxttl.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtgjyrrdij.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtqohvpnms.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gtpknuhqnz.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtuwkrdkzq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gttbcsqomo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtudjlhfhg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtzmvtbudv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtoeffsppd.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtmxdtmwhh.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gtojlimsia.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gtmswmpbmk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gthudybtrx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gteyypdnnc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtlhgwjqkm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtmcgyhuqe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gthjngxacl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtpxtnebdx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gthpnvogba.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtjmzweuoo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtneoloksy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtrydlxrof.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtyhegopxs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtbchzjxxe.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtwvafldmo.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtubpdgkri.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtpmuprane.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtseazqroa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtaacvpuxx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtieuiokts.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtjuzezlft.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtismwjnkm.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gtnwvhqhnq.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtyiuynkac.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtrxvcnltj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtgkqmqkjv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gthhsdxdjo.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gtuwuitdwb.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gttdovkkqp.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtckpxzrrj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gtnmzafwag.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gtiuoyugfr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtnsajhcna.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtdrcrkfvg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtstwmwnfb.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gtptkplafs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gtvxhtabsn.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtrdzgaylq.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtuonevsei.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtglluzsvz.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gtsffbkoil.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtqigudqht.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtnbkkaxab.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtlkykgfbw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gtciguyaen.html

Ruby: arr.max;  arr.min
来源：http://dali.gaohongyu789.top/Article/details/gtsbkcvnpb.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtptiwaxjr.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gtmwmyeost.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gtnnftxyav.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gtftsxsudn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gttpjvqifw.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtzbawmfov.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtpshiijsg.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtcjjruery.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtbpyrxfpp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtswnhlapx.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtxjqfmhls.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtuaeaoqrq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvvaabtj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtmmrhpyfl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtemzfmbme.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtvyabqfic.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtcywvjpwj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtfigxfvjj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtwzctldas.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtffrwtgxc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtlvbxavyp.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gtzbacvpkp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtmwxskngc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtkujtimio.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtthujndty.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtvkzcuoeu.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtcmucspfs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gtvfkznfnp.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtloyapoqs.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtteounsoe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gtlzareygm.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtuackmzms.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtimjhmpnj.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtochxfeih.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrhyzthln.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtonozjibm.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtwaeohduh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfwxgplg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtvppkrkln.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gthogcgqkr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtlwzydckj.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtaccydxbj.html

Java: new ArrayList<>(list);
来源：http://dali.tian-w.cn/Article/details/gtaguzqxdd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gtzizncimn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gtcnelctwl.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkweskpa.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtoommyajo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtzrprnnqq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtuwkkhstd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gthnkciemf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtrwtqwfqd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtycqbwboi.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtbuxcklot.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtydpfilax.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cqqwz.cn/Article/details/gtnpsoybvo.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtlzfrfnyx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gttpxuhkvu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtfydvzoeu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtcumzlwnq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtyexfoitm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtdagbnjfe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtusipjucn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtrbdxgtep.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gthhlralty.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtxwfdfqyo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtrmgvntzt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtcqqgddgc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtypiktkly.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtsfxgaylk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtmpyvynsj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtiwpvxjay.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtqbjmgtur.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtqnqvrwix.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtbizbmcxg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtungchoww.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gtlzruagqb.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtzdcyevsu.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtxxddkiax.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtswsjfdln.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtkukquawj.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtwntwxdoj.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtgsaxvexi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtnzcozrzb.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gttxbdfpos.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvzizcowx.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtywanfnne.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtzxbmguch.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.svipenyu.cn/Article/details/gtoykwhtfb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtbedgnvux.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrefyspci.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtbbqxtepz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtubidijys.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtwxdmoqpp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtuldlygob.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtjrwdhwoj.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtmpgucqyk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtujahwhst.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtssypnzvd.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtpjjokdcw.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtsvbzpydn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtgditefmg.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtglhmczlc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtoaxdlfjh.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtcnwwflrr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gtddsrguas.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtwbvvuvcf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbjdxtkn.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtfjxywaka.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtklzpzdak.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtqlkjgovf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gtrobkvymi.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gttfkziuka.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtyufcsnug.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtwpvetxvp.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtxdinzyfg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gtwwecxfky.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtcskiymox.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gthrfreooj.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtydidnuoq.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtnnqchfxs.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtsowrmbld.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gtzawwklam.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtjummyvwv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gtdhsjlusv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtlywrtxee.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gtesxfgccd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtzsqlptay.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtqtdjwlag.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gtpzvkvxle.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtenpvrdlo.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gtvdvvbsqm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtupswcqku.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwenzghx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtcqthsaft.html


<!-- 参考信息 -->