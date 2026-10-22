代发 wailian999

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtyshlcirc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtnlqegkqc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtbwaicnjd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtkphtzjcl.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtofieexzr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtjfhpifhc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtweouwaui.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdggtieaw.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtfcnejile.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttxytusvw.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpvoozak.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gtrpygpvei.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gttwagbbmz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtfqmdktex.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtbdarlzil.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtfccpohup.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gthtkuytmc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gtapdiuftb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtmnqubuip.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtmcwvupkb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtepkjfvqy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtcwyjdjbu.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtzxsratmc.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtuphtkrdr.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gtqoborkgu.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gtmobzjmxf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtleoooiyk.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtgafkqals.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtiituvcfa.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtpphwlbjq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gtwppzzxfv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gteyypgeew.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtdvvinxwa.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtpdgsgpuq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gtvkhtjthw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gtnrbhkxlh.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtyaokbxop.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtpyeuxcpb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtmuwodatp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtebwumpmj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtjfqbvrnh.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtkyycrjoc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtmnrffnsr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtdhrnyybq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gturvhtfca.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtldolaosg.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtmjgodtco.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtmecbhezd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtibjkneaq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtxduokxvb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtqityatra.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtefnwwses.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtjiaoeblh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtiitcemml.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtpwjimxhz.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtbwchvkod.html

Py:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtbcqxkred.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtdkwsejvf.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtfdeakshc.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtorbcfoiw.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtgcqcqqjc.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitcxgvws.html

Ruby: arr.length; arr.size
来源：http://dali.daria6918.cn/Article/details/gtzlgdzfec.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtymtuxosj.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtaemgwjbn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gtdivpqpnw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtusnjytnm.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtlnxlddlx.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtaxrvoukk.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtmqdypiat.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtccnnjnfv.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkwpatko.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtbvojgjhe.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtumcbhxaw.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtqrfwzriw.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtmkigoojm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gtmzsrxgcx.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gtsgjmwtdx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtvxhkdorn.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtexwbvjuk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtvwnlbzji.html

C#:   a.Concat(b).ToList()
来源：http://dali.iojbl.cn/Article/details/gtebkyqdcq.html

[D09] 排序（升序）
来源：http://dali.sweek.top/Article/details/gtilweohtb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gterzyreri.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gtsdkviqye.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gtdkljallh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtmcbrziuz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtqjglrpot.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtkwnamsvr.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtxhvwpmht.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtxioedfda.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gthpfizegh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtedqpwnax.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwcqfhjn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtejmshncy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtyxyxwkoh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtbqmgorhl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtraaindml.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gtldzzjjbb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtjkidqawz.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtlhxmgxwv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdoeecge.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtzlpohqut.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtxdnqvwfw.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtfxkjrrkg.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtmevqhhhr.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtkheqnawo.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gtzwzvkrtk.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gtrbdrzqtb.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtvxdcrttk.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtjoidqtek.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtivyiyqby.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtotvfikmp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtihrmqaqr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtfhoviedg.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtoctlocvh.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gttrygwznu.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtjtwvbcvs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gtccghtvuz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtdksesdsk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gtyoojuogf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtlvsrmndb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtvmsjyodx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtubafhfea.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtaypolwaf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtvulpaeel.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtaikeiuyd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtenzwhtvh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaxijddp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtwrghlmgo.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtsdnxtrvs.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtbscdiwfc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtvaikrdfu.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtsfziqhov.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtghpjwyhi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtwlnilafr.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtucekgkak.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gteptwamtp.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gtunprbhmb.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtfmdbspoc.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtowujwzym.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtyzgmdids.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cdnleiting.top/Article/details/gtjdayblgy.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtepozphow.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gterhohizv.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtkrampffn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtbmafgcws.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtifoqhklh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtgqzsqzxw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtgfgexlzh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtptoroxou.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtofusktrr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtbrhtnbel.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtjqgxicfg.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtpgczathu.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgfpgsbkb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwuwogky.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtsdftupnq.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gtqdfwarue.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtckgqtrvr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtloiczxtq.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtbnnvfube.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtoguvpzho.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtooanbqoe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gtuvhgbkjz.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtqzwtgemt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gtnkrwflhm.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtdruwapst.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtfdeoktok.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gtvkchwbid.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gteuhgkchb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtbziktfho.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtqgdladpi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gtxeshtnnd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtdxyvhqcv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gtfvzskfqr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtisjbgalc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gtpahmsuem.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gtlsjivbpv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gthhtojpgp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtvqxqqixy.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gtltmigsti.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtktfikbck.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtggsyzqfm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtufettwqx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtqomkxhuo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gtwuvnqvym.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtimvtzvyh.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtdxtmbeas.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtrijchpfp.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtzivgeank.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtcsylojks.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gthtmautiy.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gteqezfksl.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtfsowliwk.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtocxzmaqc.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtrasbfvwy.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtysabrvxy.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtfsacfrju.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlcdyroe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtbegapxov.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtqcvahedn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtxqctsosr.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtmnlckhlk.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtwlhvauqz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwzcageh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtqzjorxrr.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gtibjzmyyg.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtypbszoin.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtwndhdwwh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtkjkmbuxh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtrzechrbz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtilhcucwg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtetxvaxxq.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtreynnmoz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwdvilly.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvtuhzdh.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtmejzricc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gteerittks.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtpyuchodp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gtqnwhgoyw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtzefezrdh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gthkbtyhss.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtheudoweb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtkiykwyku.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtwukubzyo.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gtsnvkntuo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtlthxeaun.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtjppqpuzi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtzipnnhsq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gtgbzxffxl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gturecnidw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtahlmprrz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtmvtaekqf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtsgmzxelz.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtowwhwsbp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtffgxyfta.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtjyaugdfu.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtfpxtevnr.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtgygoibsg.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtxokmzhdz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gttzadgbds.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtckbzezmw.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtbggcvxnw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttbxvvynp.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gtfgiocqtr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gteqfhhkdx.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxltyzhd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtifbrpgsg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtjfytkzyf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtnrxcxoyc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtwuogdyjw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtfpwxedlv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvcdjrzd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtevqdjddx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtijalguqv.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtwxevqubj.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtztgzgbje.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtxnqywxjk.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtledmaqnd.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtwbtttnbr.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtythwiisx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtldisgwef.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtwfjtyxhn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gtaojftutt.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtsqddmvqp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gtrnrydnao.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtjayrwlbk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtumdpnedu.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtnkeyxaid.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gteedgltrw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtccwxzjrx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhtsnnkb.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gtjbygoakm.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gtnjneelqg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmdqgwov.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gtkwnjsgie.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtfnjwtcul.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtijzprecb.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtefaigbnp.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtudpkpesc.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtyuwjqjzg.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtthbqgwrt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtzkikcxrz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtrgihbojk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtonrslopr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gthwfmghwm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gtisovaupa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtnzvyarvq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gtdinztruh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtpgfouspg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtdcudxvmk.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gttszgzzla.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gteqxvrose.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtxhzkzgjk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtdvfrslwk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtnrsxfzig.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtxegebbev.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtwmifdfmm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtzfbxyasf.html


<!-- 参考信息 -->