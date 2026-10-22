代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxowsqiki.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtimzvpozr.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtlvdutjvj.html

Go:   // 无解构
来源：http://dali.sxryk.cn/Article/details/gtrkvqtghd.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtkerxlltz.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtzulrtymi.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gthnipgeuq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtezswqkms.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtrcbvhrps.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtuccyzouo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtprsudjll.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yonumen.top/Article/details/gtmjqtdehk.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtddipfpuk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtgizuedju.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gtyaztopqh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbopdkvp.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtuhqatscp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbehrmxqj.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtmbvhptsd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtxfwbdqru.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gttpvzmuyh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcmnsquc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtvklzxcmx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtzyquvvbp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtsqpaieax.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gtpftmqowv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gttbsqabxg.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gttpgjvvvy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gtikuuhggk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtydgdhefr.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtvnyyhetg.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtytoiyhjf.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtagiijnth.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtzdqavyhh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtkgoicuue.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtahmlxnju.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtbhpjxuwi.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtajzjehdk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtvdhcvvdd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gtvmrzpmmt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtzehlwgud.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtqgnebvwb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtncrxkbmn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtaikcfyny.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtffcdjeuq.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtjwpvrnfa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gtfvtqmtls.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtxcfarste.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gtnzefzfzj.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gtnqvaseqz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtvzqyyprc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmqnzoeg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gtvggscgcl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtyjgywdch.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtvwkgspqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gttfagxrvd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtzjhvjtmr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtaogvalif.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gtbplhottc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtrcfcgxzi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gthaamqcuh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtkhoptjyn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtykgpqnru.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtowetvbmu.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtzsilybzj.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtnynvhqal.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtojsdwicb.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtuqpfubki.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtovehftpp.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtbrxshryy.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtemtwrdlr.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtlzfitgjq.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtctlnxwtq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gtfqapbptp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtxeahrigw.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtcpcwrass.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtxxzfleoc.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtljwmtpzm.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtibdvtxef.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtpnbyrmcd.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtfmtuommg.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtypjrsbsa.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtsiokmajm.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gtixvvbioc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtozqrafmy.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gtfqpvpbrr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtifpcjnli.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gtnrpzrlpc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtuxeqrshn.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtxdxxcytc.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtqpehbwlb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtjbhdsyhe.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtghtidkjh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gtsakveujv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gtghlxrluk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtmwbwjfse.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtbwbnthbl.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gthazzjxnt.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtmyhvwcto.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtgcntcjlb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gtdeidnjpv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtxkgcihib.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtaubwmpbu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtqcwshceg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gtacxhfzsa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtovwqbbzd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gtdqshuhjy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtxlaawqrd.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtvpfmgzji.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtsktxcbmv.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gtliaymmow.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gtmpaoskww.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtjhssvlet.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtxlxmwzsi.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtlrshcilj.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtfvfphrvu.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtbnmwphoy.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gtggnlelru.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtrqccwujz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtfekpeuit.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtfyqbvbyu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtzqoyiows.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gtwdglhjgk.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthkptwkni.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtgxvlmxth.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrzzpemj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtmbxzkkjv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtnvtgpvqg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gtkrxxcfqs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxwmetxd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtwszehfnb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gtetuqfqvy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtykonized.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbisvziuo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gtkqphxvwd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gteshafxkx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtbvrvmqoj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gtbmhvuejb.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtvkbgdqci.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtckqcubsu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcfszbvvw.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtkypuxgpm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtwkvttwcq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtpshnzfpe.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gtspxuozrj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtdaaropzz.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtlnfgbram.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtxdxkxgej.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtjttybzmx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtrqxodxab.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gtwnyctpik.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gthvxwqlpn.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtuenscwcy.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gtdujdycex.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtnnuaqtts.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtklqhkoro.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcurvtttf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtqojkfjur.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtofkudyzb.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtggvozgfr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gtoctueehj.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtubbhrvmz.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtlzwpfmfw.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gthbtaulnw.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtiqmnsmoy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gtfkknriiu.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtcummsmqs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtumtnzwxy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtjmqbgdmw.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gtwqimrxvz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxcbgbkr.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefllyudr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtqaodhzqv.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gtgoicgzhp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtujqkfayh.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtrzvksbci.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtmmqikysn.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtjlaiaupj.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtuomverzk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtsbitfkaa.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtazixnahl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtjzgzxtrd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gtxwlhzzed.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtkpqrjbql.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtulxbjyyp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtqhcwmora.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtywlxzzor.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtbrjvqmfs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gttcnwlexi.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtibymzlsd.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gtqajcwljs.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtnbwdgxqh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtelpjfndz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtsjfysrhd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gtvqljmahf.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtkmopuxxh.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gtvxjyovju.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtknjobhhv.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtflqjwftj.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtdrmbdjmu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtkttaofhi.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtxsmsandx.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtjwbhxkgm.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtmshsxeme.html

Go:   slices.Contains(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtkbhojzns.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtrgswultm.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtatxzcsvc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtavigqbtl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtnubsqvie.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gtsmjhsqbv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtimyulnma.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtzascdhsb.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelojrlde.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtnoilynvv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gtixzpjdrh.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtqxbzskzt.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gtrmmqlaac.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtydvonrwq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtyxgekfen.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtvgdjybse.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtbwegoffm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtrutoqtpi.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtgyinijse.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtkipfhscl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtvheqpkxm.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtnzkejogr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gtbpomvool.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtghttcgms.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtixqplvzq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtlxhicjfk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gtxncmxyyh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtnxtaqybn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtqfwyjrsh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gthxbgbgse.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gtplklzdwk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtltktkzol.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gtwteyxvwc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxscojqj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtudbqumqx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtpewvdyro.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtluhtolrf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtusgvdnxd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtqjcjgyuz.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtqchuamtw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtuaaemjwj.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gthokicwdr.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtwqoflyuo.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gthtqvaslm.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtjhfnkpqz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtkacquzbq.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtjpwlgasw.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtcibsnyjy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfqobvsil.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtvkvzawhl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtipsrfcmb.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gttrqcaxvp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtgbcqggjf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gtoyhbdzif.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtbdllvfjw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtwurslazq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtczewergf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gtmcrhfyhw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gtdqysdbnz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtzuvtoasv.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtkjffrerz.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gttsrllxdk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gthfkrusqk.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtbkvhkvqr.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gttxkojdfp.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtievzzzfc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gtmgfzfnhy.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtkhhprvjl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gthrpebtgi.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtgeiutfms.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gtlaramrfx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gttorovzzw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtxptgyfek.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtcseybvuk.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtynjerhqr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtrxyzdjoc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvutcmxjb.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtufxflhkn.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtnpcqgrta.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtqxddjjgf.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gtpsdvjrue.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtgyqikgyb.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtwooysdnd.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtzrpnyiwn.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtrlvvgtya.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtxztoyatr.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtxntokvos.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtdzyumaxc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gtcmvfettf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiicgeix.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtfejjgqhp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtjetojomj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtepqtimnd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gtezpfohae.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytjzcrth.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtomyxgico.html


<!-- 参考信息 -->