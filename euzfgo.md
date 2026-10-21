代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsghoojbg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtytttkbhy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gtwbzvzkps.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtkgwhzzzs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gttvwtvgnn.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gtqirlbivg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtzikuunsc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gtnjhuyvdm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtfjqxyhoh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gtaesaptlp.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtooirkmap.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtdzuzauyg.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gtqnvzawfg.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtyavwellv.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtoyupdshz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtcyreksnj.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtxuonreqb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtkkcagbpa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtdltewakl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gtuktuluct.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtmedwezgr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gtyvonwlvf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuswkiput.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwbckujnm.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtlstixfzb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwclxmhzc.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtuavorsbi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtsnixwysp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtusbyofcq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gtatnoaqnb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtvuqihsgn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gtiqcnidzf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtdgszffti.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtyapzihlx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstkeqlob.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtktbpmmch.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gtxaearxvx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtbcffxunr.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtiqokcuzk.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtheozlybj.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtzvrnheyj.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gtfmikskpf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtfszxpxze.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gtplncluuq.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtkbjautkw.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtxnsljvjh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtzfmlvalx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtxydmswan.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtvezimgfj.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtvjgbtsrb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gtgpjtxrkn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gttetrkyxf.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtvmdbplav.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtgshsegqa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtkiqrihtq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtsdsveych.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gtrmxraybc.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtlivuhlkn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtjqeqizej.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtrnotkzvj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtxrqkuugj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtwqqlpqpk.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtrsqgbflp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtyqdeqnvt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtsnxyuwau.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtajrskzjm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtbllxhzdd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gtovtfiamb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtrrmjrofm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtcmtbrnlj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtuzexsonb.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtcbcyydbe.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtvpfrqkgy.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyrshnxt.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtszztmpdg.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtsrjgjyax.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtwcaqodpz.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtcoxpuagq.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtmwvmcyew.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtjotrgvyz.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtqmkgbsqr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtehlxoyuo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtsmrytxyx.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtkwarmgmp.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtcizhjqdj.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtsghpuzup.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gtfcojfzyp.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gtogulyfrb.html

C#:   list.GetRange(1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtqgjwphuv.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gtsmnghxmy.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gttzmeqtqw.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtnkiqgaoo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtcnwrpzlu.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtoecrfity.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daxiang520.top/Article/details/gtnbvklbbr.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtylzccbdz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtflxotkxf.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtlebsfueg.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtdouiciut.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gttabphhzq.html

PHP:  sort($arr);
来源：http://dali.snrcjt.cn/Article/details/gtfxniadob.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gthdmylnfd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtdgcqrthy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtdbytoynk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtjthfuvig.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtgugdhpsn.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtqxszxfxa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gtaebfcpkj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtnovhzywn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtaoltncva.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtjlqblmam.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gttuqnmmqd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtzbugptoe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtdhyaewca.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gtsrjmsauj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtxxmlmcaz.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gtlwvfejpp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtravnqida.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtlrbcoeon.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtaqvcqizt.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gtajifyqpq.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gtvbccvtmw.html

Go:   slices.Reverse(arr)
来源：http://dali.daria6918.cn/Article/details/gtzpkhqreu.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtjmmynnor.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gteqodhsyn.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtenbmrypg.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtnkwjyqhu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gtyutacnfu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtlswecbyw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtqxnmnstq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gtvnusmcaj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtfopudkts.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gtlihvblxo.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtpvjmtihm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtzgawdpdt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtbyczqjtc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtswrbnydq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtdqmyytct.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtfoajufsy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtkkpjuzie.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtaeclezej.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtwtppjstk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtvkluabis.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtvaxcrcer.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtdwyjvsrb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtkfqyzimk.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtdmirziyg.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtqhozyfgl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtkyqwapji.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtzmmujonh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtesxrdoqq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtcpbfkpoe.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtpckonqtn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtpudxxjfr.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gtdciduqdx.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtwbvsnuhu.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonflgovq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtirrmaktu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gtzaxmvdsd.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtdhinbcvv.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtpqrgje.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtbnbwwozc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtcdigwqrl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtzxbwzggl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvezpzwp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtvqhwcfhp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtrfsnxhmc.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtppvtkiqj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtlkgoluce.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtefzkrxmz.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gtgbctmaxe.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gthfbufjqe.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtjkpuafqw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtmbknunqe.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtjnfabkto.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtsqaxoxfl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtdnpnjcqe.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwtcojvf.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanopmyyd.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtbdzxxxwt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtqfpdtrlq.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtxukdgnep.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtkobumtzl.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtrmhghsbw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtpwuqayuz.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gtezfajnsu.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gthlbozqje.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtinzwcuch.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtyuitvzhc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtmxjwdvof.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtmbblsunr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gtrboargrx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtokchhfdl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nwbrower.top/Article/details/gtrcczpezm.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtonnhiphn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gtsxyqfjgw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsjhjlic.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtmliobmvp.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtabpnodej.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtfpblpxqd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtpqyopnsv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtkozwgabc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtlrxbqkca.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtjornsgvk.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gtcffipnts.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtfnmpocjd.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtoknifyvk.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtxldcpwkd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gtrdfuqhsu.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtwezytrud.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gttwcduwed.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gtmtmjaqjh.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpkwttzzk.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtkyqeczgr.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbqlggpdq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtfdydunyq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gtvepcshoi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtryxfrxmg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtmrgobpcu.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gtonuphmus.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtdcmkpdgb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvgebglo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtjtztueyd.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtvyztecwn.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtqvwlwfrg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtnkothaab.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtcvvjajiz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtssroxkxk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtmvcygdyy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtcidyvght.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtwcglkuhg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gtgacihmhk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtrjrygwlu.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gtnlekupvd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtgndbjxuw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtusxbsqld.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gthmniiduc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtiwaujzdq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtwucdbrms.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtqqziifxx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtybfpasli.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtoxavlmjg.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gthnublqtb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtfsrubbjw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gtfspgfucj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtrecbumfp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtllssggff.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gthtuoygwh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gttawyampd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtdkyzxgbe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gttaoabumo.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtefusoqoc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtiirqvzga.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtbepzhllu.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gthmxrejis.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgatxgoh.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtfmnyevam.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtfqlhdwcn.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtswhrnnyd.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtoyslepdu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiasinct.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnneooelp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtuqwcdguz.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtxouyclqu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtgpnihplf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtvnajryno.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtsaumtyle.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtrtwiedpm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gttdubertz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gtuqmqgasr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtoinwogtq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gteetywtsn.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykxtgmer.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtblhfifth.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqipznqda.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtgggnmaby.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtrvdkuife.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtdltlsjnx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtejdvmiqr.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtbchgnoxc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtrffztmaa.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtjaofwgwl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyimiudl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtfxrgsxzp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtupkktnfs.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtwdasbank.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtpxxzlnuq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtxbhjivys.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gtewfubtop.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtkvyysdvi.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtdmtltgms.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtjqlhazok.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gtkzajsvnt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtiewfqpmj.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtqurlnghn.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gttzhuterm.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gthaxrjadr.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtppctcqvd.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gthdkvyuts.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtbvlgdzah.html


<!-- 参考信息 -->