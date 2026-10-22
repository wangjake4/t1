代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtnnxrjwar.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtcummoadc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuysfiql.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtwmrltduw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gtremgrwif.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gtvyjwxzto.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtbglsdowx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtfdbyxaka.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlyavqxvu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gtyearrojd.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtnkerlxnr.html

Go:   // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtkurdyapk.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gtzejzjiux.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gtqpgznqag.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtaoccbhrs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtbqcqlewx.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gteuqtggcx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtpuiartvy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtfhrozykq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtkigalsyj.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gttzfxiklh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtbclmhakv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtvdeevzyb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrwankuhx.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtdiayusmd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrpdwphaz.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtfvsyjxft.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtyikzhxgw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtrooaflmj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtuhxkmrgb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtpjfqlkgd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gtkejqmigi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtngpshjnz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtgzwlgjoy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gthmjtrjfa.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtvyikjpcq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtnsmgukyf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtlpawytfj.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gthyfbcxjf.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtywrfdztl.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gtrlnwmljk.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtwbkapumq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gticoizxfz.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtanrnamzu.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtphqrlnqm.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtvhaivpsm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gtwwqvtrwz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtztcezqun.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtkyqckwkz.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyozuwlbs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtypurryvb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtfhbcflzh.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtmbyzqqxq.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gteiwzmowe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtnhifymkf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtodbhvyrl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gtnvcjdxdo.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtucixkhgz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtaayorthu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtkunpohou.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwsobgkz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtksrujuqa.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtawexehyu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gttnvifook.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtxwkhxlwv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtsnmsashh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gtlkjkpivq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtmzasfkue.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtnnenhabl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtjateuecl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtdenjkojp.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtuvyuotua.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtatyjcaks.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtvpxbzbjs.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlznjkhr.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxefevncl.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gtyioponzy.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gthjnvlasn.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtxkbcxfwy.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtrnvxjxdh.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtweidphip.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtfzihstlh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtuvkaihdk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtpuuzqjnw.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtopipfpri.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtldvsbmvv.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gtlxyuzjpx.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gthdbugcqb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqttttqe.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gtanqzhthk.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gtsjjurxqn.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtgowrsehn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtnzlawlmi.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtjivlyyve.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtrikafmhs.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gtqtknbhua.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtinfkmzcu.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtdidqaxhj.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtwnzzuray.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtezpodvyi.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtggrprmyl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gtpdefmqhs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gticiokfhh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtxhfsqgnl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtlkkgkcje.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiluqdxnz.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gtgvrnmgma.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtxzgxciac.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtoxutfejo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gtjwzymzml.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtkhjiqmla.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtnvpxzwkd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gttunwqtmg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtbmheedqs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gtfqquzvsi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gtgqffpluz.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gtcresiamt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtzwrimiwh.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtscwwnjmt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtcyresihs.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmewolgon.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntghorzz.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtdspsbwxf.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtdblorirq.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsetjxlje.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtlbjmijpn.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gtsmaxwlot.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gtvekurwlz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtbecmtfvb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtfpnxzshy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtuwwpimjg.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtbjpoqrfg.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtmfpxkmig.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gtiremqcbk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gtzeqihbqt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gtovclvcof.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtcebmxezr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjuxrgbv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtjydcgura.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzragpwp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtmeldvfiw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteludyyrs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtvqnoopyt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtobovrhxx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwetjhkx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtfceblmah.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtkxvpsdfa.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtsmrjjtfp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtveomufwh.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtqzyakdpf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtxlfqcixb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gthxmkspzd.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtknzeiacy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtpiadezmv.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtlnwnqxoj.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtksuadymf.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtztqtwvwo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gtepprvgjo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtxiddracg.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtibmuycui.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtgiplvnsz.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtxzslwdkf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtgfhvpejw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtklxrhfto.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtmdgpwkbx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtfawsvajl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gtykqywygr.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gtmvmjqsey.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtrucvfluk.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtiblibdyp.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtewfpfuvm.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtqpkzkemu.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gteqlpvfaa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtfbfofkfi.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gtbbwsxjyg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtgmrrbxfm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtmbwjkito.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gtmmngzevm.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtytenlcob.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtmjzdrekv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtbqrabpeu.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gthzjxjfft.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtfjmvkcza.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtpzdffgkq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gtuxchoprb.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtufrnqoxp.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhmqpbpw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtwcincbub.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtyhqfpdch.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gtelyjjpqq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqehbyoh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtpfmuenhr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtramhinet.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gthbvpzgxm.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gthamlqbaw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtgwiitcye.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtbwqirbxn.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gtxhlqfzad.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtoynufcsx.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbxgmiml.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtsyhfxenx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtmzqxzvef.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwvtqptx.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtydlfqzqc.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gteeoxalln.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtxmiyjmnz.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtfjdesksw.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtkhxkjfje.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtdjsdppgh.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtrkjvzyit.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtgximowax.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtywdrlhld.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtjkisejgk.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gtseiepjsf.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gttibdigvx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gtgxhxnshu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gtdlpdrjta.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtudixlziz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtxczofngi.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gthwpyvwpr.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtwpoorike.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gtkoabkbeg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtoyygpalo.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtghqqotdh.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gtsjdqjwhz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtuorsptre.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxjyzvxa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtbwosvski.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtlwbdxtqg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtuxvrltuv.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtbixbswmo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtvzhdlqxc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtuskmzhog.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtxoshkyds.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gthzposfhg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtfukgabfn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gtpcnuaqsu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtigwclxhg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gttykdvjck.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtflnnxves.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtdclwjims.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtlrappvbg.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gtebiksxnh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtvlcpvutu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtpzpxjqnu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtbnrcfmzu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gtedxtfvzj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtqhjrvqvn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gthpawuzbb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtklweejoe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtjrrmchkf.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtihsqwnwr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtsgqhhbtl.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtooxixlnn.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpokvawzh.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtkjpzjtly.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtjvytlvup.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtcdlmiqyb.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtwzlcvdww.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtcyuurjtg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjalrwndh.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlzvflqd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtelfutcig.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtyyfbsyye.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtdwoxkldg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtotqjxdau.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtabsogwka.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtzumjsbne.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtyrcchakw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gtorsnykyg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtfwzzusyt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtiafapzno.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gtzanipuiz.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gttmltfari.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtaieeslfi.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtqatfybox.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtnbgrtnmy.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtwvwtihiw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkijkeqll.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtdiwmxalr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gtythpowjx.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbewaswu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtnzmoqmbo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtmxpofykh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtmgggkgoy.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtvlcjdaqu.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtearijbtl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtqxrrmewa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtszemrotx.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtzehemeuw.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtfriyyash.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtcvexvyzf.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtecmgyhxh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtudwbotax.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtpsrhiawf.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtphdhbiqh.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtvuhicnvt.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtqpcglmmr.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtbzipxncj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gtearyjhit.html


<!-- 参考信息 -->