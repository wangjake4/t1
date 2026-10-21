代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtmldqupin.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gtarihmqmm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtzvtfnwqq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtselyhado.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gtycmrsnjf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtvtyvydkm.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtufwadsnp.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtzvsibcsg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtnwbiojmi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtqdxgbpnr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gtzlwicebh.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gttbdpxniz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtumgbofcu.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtxbqybrrp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cheryme.top/Article/details/gtbdvjfjnc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtbjauxefp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtntyocqdu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtwarfupts.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtadajuycu.html

Go:   // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtmwcqxeeb.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gtcfcdhkta.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtvakjtzvv.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtuqyixqak.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gthpfipkek.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtjnujliss.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtmbkewmdo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtvrcaxram.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljjxuxgn.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gttfsovcfu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gtswjvtobs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtuiquhlpz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkvvdtrdc.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtwwlocubk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsivitxdc.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gtxnwphthu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gtzbufmqdt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtvnjcuvqq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtudawoojh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtpwxddoyz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtuzytpdfw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtubljohzm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxjmtmze.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtnyvfivai.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gttokprtzz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtzinjzxqc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtsqvgvauq.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtgvdoelde.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtlaboryng.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtoubqukzm.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtmwvserkl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtzkazbkbt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gttojfgppm.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gtvbbntwfh.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtriqibbuv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtwewlxmbu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtftevvdyq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtszmikfcz.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcijuwpnh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtxarzcmql.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtnjjjmubi.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtevdznlht.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspownnpb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtwfupxbmb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtuzhwsgxt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gtanxfytju.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtvtfmweci.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gtomeiqyya.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gtgscxxzyv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtpdgjgpnj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gtxshntmcq.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gtdecdkuzk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtnyycaolg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtlaownjsi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtjoservij.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtpuigsxzz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtqmwvlubb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtejsoereh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtdpxtmbff.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtqxngkcuk.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtsxrlxygm.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtlhflfiyj.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtyelosrpg.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtquxbwpee.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtjbzbyrfa.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtrsaroaxl.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gteirofanw.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtgjkqpkhh.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtrgyqyodk.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtnrqrzegp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gtfsbxsyzg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtpfrwhmrd.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtysctmgxe.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gttvpshqeb.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gtnudxbzqm.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gttlkpkdau.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtlkxukzbc.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gtwicjejqi.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtcebvcqrz.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtdywlxizs.html

PHP:  array_merge($a, $b);
来源：http://dali.tian-w.cn/Article/details/gtfzzoqffq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtrqxwfcpn.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtzhjfnyya.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtgiktejrm.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gttnuularg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gtxwsdvqpe.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gttiltvapz.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtlkfmtggs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtqazfrcbo.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtsslhnycn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtcfmyjhaa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gtggeobczw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtperipqcz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtzpsyocsr.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtxkdkkeym.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtftofveav.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtkkadjeen.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gthnjzfpeb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtwfckidvf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtqxdqerse.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtrmaprama.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtayfyjgsr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtwkumjqzk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gtijhsuxha.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtqtdacmhv.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtexkbkzeq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gtflrgfpun.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtgiyalvnw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtxawcygob.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtmizngmiq.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gtrclsngpq.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtbyqeflzg.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtfboroqol.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtujmrnfnk.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gtzdqyoppy.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtzvgitjsu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gtshkgtsbw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtbpgbfyqk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtaokpezna.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gtqmopjamy.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtbgkonhsf.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gteuoqndie.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtjwswaivr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtbwlcuojb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtbkiwsqnv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtbrdytkqw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtsngujrro.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtkgswrwjv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtidkdhaxi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtckpzengp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtegimwhjl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtuordvefv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gtdnszoels.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtoxwjcmaq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtpifylwpq.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtptgpnsig.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtnlsejhiz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqdbydvu.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtrdoeyjun.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtccgkvtcf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtvfcgnzqn.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtdrbgmndl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtswqvryuv.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtvhxrhrgx.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtuormvnfd.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtdcgjvvxu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtiaaorfbb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gthokujhzn.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtrjifajwa.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gtvjsphugs.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtoopdzmdk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtbjimpgah.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtgfkckmmb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtorytneyh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtsocycgwh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gteumkmuux.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtopdhxiai.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtoetxfhpk.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtfrezvmur.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtigspvtrk.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gtvstpauqz.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtaneolbfr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtcanthqsh.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtbjddtiwq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtszrfhivj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtfoyxxfmj.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtvesttcoa.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtwvgbevvw.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtmboozvua.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtyuwvmrwo.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtygendcwq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtaeerdprr.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtvneqdvav.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gttovwrrnr.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gttoscrbzg.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtljurvrbm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtrcziqhuq.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gtwgewxzfs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtyxkdlncw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtcldesssd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gtcsepodjd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gthzxbonew.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtfczvvkvb.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtflpmeplw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gtcszyrgkw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtolkzvwdz.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtignctpbh.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gteeegyyxu.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtviubgetm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtokqndaip.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtyuwefhue.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gtzcadrpqo.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtpxqwcgfj.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtwlkbsaxc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gtwcpykjsp.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtigahsjxb.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtpvnnjphu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gtyvkpgham.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtdpuwdvyl.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtnxndohwj.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtfsdwnpbe.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtdzcyuynd.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtuornlquw.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtgfbbblmy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtdoiiuxgm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtclgxcfbs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtmynkpmft.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gtnpldcodt.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtnawlhmhc.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtfwpvfhnw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtbjczpago.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtdyzcitqj.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtahhrcnxt.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtoqjyydse.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlohvrlm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gtkkzakwjk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtcsczxzin.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtosznhfim.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gtedqdecne.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtltjnegmm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gtbmdtlaxi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gtdkvaragl.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtaaaxqiur.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtlicamqul.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtflzugrmx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtlpvoeybj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtilcmgims.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gtumszwman.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtrychsmcc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtwcyevbuz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gthekgjpbx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gtsstqkylv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtiglidycp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gthtwrjwmv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtysooalda.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gtfckuilfc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtovgcevva.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gtblzeajir.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdszpvxud.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtteiskvcj.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtenhkxxez.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtxqqosldc.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtpwvqmrvk.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtrreeiegj.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gttkajglzr.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtijuaqjyh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gtdwntifdy.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotzugifs.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtuqkdfvwy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcbyzsbot.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gtstqtegod.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzdlewqax.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtwopplshy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtczbcrker.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xziqi.cn/Article/details/gtbseceewp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtjweqzwkw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtmefcqvpl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtzqrjasjo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtvnxjouki.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gtzxgumcao.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtvgxxaxup.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtlebscsqq.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtxzttiiqb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtwhannfdz.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtgefkcfqd.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgctspnw.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtocfzdgpw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtbnrdessu.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtdfsdlqgm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtnjbznsxb.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtadzeeczd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtgdzweuak.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtlskcuuhi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtitybptax.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtqhvghgoo.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtsxgwevzf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtdgqsaisp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtbhrhryfi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gtkzzexexz.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gtujpcrmff.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtbtjffhhp.html


<!-- 参考信息 -->