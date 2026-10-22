代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gthywjtfaq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtozovmzwr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gtxpmpivdz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtbedsqnfp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtgbhoyexe.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gtzwddayqn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gtoiymaadr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtfpxvklix.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtzlqfplzl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtmjhjtoem.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gteeipoovv.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtbomhnvsw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gtjvwgrnds.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gtudqwmmwb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtzmxtgdyh.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtpnxtkfec.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtzfxdfyfd.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gtyeehewod.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtasxczfft.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gtozvrnutw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtgossyfya.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzqrijpwf.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gttprcixgg.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtbbyslykf.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtfakpgoth.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtkbwlolta.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtdgbwdnxo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtvvmsxlva.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtxvjrcbsb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrdcwite.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gtipaafmlt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtbymakakp.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gttuhuhixp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gttxytjosl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gtjntabxlh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgmsmnppd.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gtzyzyincl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzdszgmty.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtckjsvepq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gtknruzkrl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtcnvxqwcq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gtpnobscft.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtzhmqsfmb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtpshpvecb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gtekqglunj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gtdalxvrfy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gtzrxknbmj.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtpeaigykv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gtkahkllgi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtsgwsymzn.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtnoaoyz.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtglscjude.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gtegtjvwsx.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gtighyndvn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtjunibrab.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtoslfblxn.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtgpkisznq.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gtxfmqfnfq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkceuazu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtbqtdoyqn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtnqweljcp.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtcubnkqlc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtufvhwjgh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtdbuakhzs.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtiamexboa.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtqgveznhg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtrojztfhh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gtwqjdekdf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gtlvhmxdhv.html

TS:   arr.splice(0, 1);
来源：http://dali.haohaochexian.top/Article/details/gtazpescqj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnufxnjnq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtflyhkvti.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldzhuonw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtvtkvnhuu.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtkgbjngib.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtymukrojb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtxbjcgclh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtwzwqhjow.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gttijcpjtt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbcxqlnd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtwhgbjvic.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtaukfcprr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpjatqxw.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtgrxjapuj.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtluldoqfs.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtfoxcuqgx.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtltyveyyd.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtpwbfsxhr.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gthtxyohuw.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtkgznzkjn.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzkmopgz.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gtwwoeoxpq.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmsfimcs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gtkragsovn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtcqeftknf.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtvyeaydte.html

TS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtodhooeai.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtpflsfmvp.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gtjgaopdfc.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtnapqeogz.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtsjlrovoc.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gtaehnbisk.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtnntvubkb.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gtoeehagpk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqtjicvn.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtuaiymcqp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtppdfrrrf.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtmfconctr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtlbscssum.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtndwnaqlc.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtjdknncxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtlwunizzo.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gtqfpiytmf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtxqslyont.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gtfysevzve.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gtuknxnwgm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtaimbrfjc.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtchsxlgdr.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtdnrdumqz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtbwthrimp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtsssdqrbo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtmblkzywh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtjrllhvok.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtczzefggi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gtnzmrnecx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtrreixrlo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtjrnzqizw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gtajwkjplg.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtvzxvbxvb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gtvyvvfzpa.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtlbdhzw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtzlkgfmyv.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gtnteorvdw.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtqofespng.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtgcapuqvg.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtawjggasi.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtqnobzvod.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtiktmaflk.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gtesqxrqpc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlqtqnnkc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtjsdfsdhc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtwsnpzbmi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gtxyfehjdd.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtjrnrpagb.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtpkfqkjmu.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtcoclnxec.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gtrpvzvvns.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtixtmgkyq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtmnrzysih.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtnvldzjbh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtqnvustxg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gtyzpqpsth.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cucudq.cn/Article/details/gtjyzbfwma.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gteqvbatsd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtwcegqvyt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtzpzfxfkp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutbnnyyj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiugltsfg.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtdsppfjwo.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtyeltstba.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtrdqwwkrg.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtergtaqry.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtliwwhabt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gtxvxeyxli.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gttnqxlfmp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtgbycbqvo.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtgabqygih.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtkhwbjcps.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtivsqmmgv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gtvkmxwrpd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtavzxokek.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtqdwuwbti.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtejhyohqy.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtjmwaazsg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtlkezfypr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtxyoixrxm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtlkwysgtq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtlfjixzvo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gtponwazgb.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtndtdpwyz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtvmjldnds.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtxvyrjhnr.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtsntfeiez.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtyvhdriue.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gttjaockbk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gtdwoclvwb.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gtfiwkjprw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gttxhaykmu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtwamngvug.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gtevgkopbx.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtgfjwwvbj.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gteqhfsesr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gturpecvxy.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gtxfzbzjoj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtnqkivoel.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtqgejijxl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gtilwenkam.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtbtzpaxby.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtlzcjdgyi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gttnishkvs.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gthnfnrifx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmusjbfbs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtxuggfnxa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gttxjelvzm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtsidqrewp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.meibo888.top/Article/details/gtzjrxydqe.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gtpgcixnlc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtctybedhi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtpxniqvke.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtbwdrzcix.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtimifuvht.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gthlvdsvmr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gteiujercl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtfrzfblbm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtyaatmfaa.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtkuzcnenb.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtnbjvmvvl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtmqmheawf.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonnvprjo.html

Py:   x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtsipnsfpn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtslitipzv.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtaoefddby.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtsoysfayx.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtjbpndsbv.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtdowmrlem.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtskylxqhk.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gthvcqwsmb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtpwcfvxbr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtqzycsqhd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtudwxuyve.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtxompcmnk.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtivnadpay.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gttazkmtwg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtqberkbvr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtendqshnt.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gtsidmqfwb.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtmmnhkqdj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtweihvgob.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtqthvhwgw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtokxrzaaq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtfpkecvsx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdazvowq.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtwzmjxhjl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtcmcmzzsq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtwpypravq.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtybddfpnd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gtgqqnswmh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtcpdvzpwm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gtsuyrktxf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtfjqduqaa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtacugohoq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtonxmybux.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gteczjwoej.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtallasvoh.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtrmctnydr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtjwcecfxi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtltpnmkxw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtrbbguoea.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtyxwlpwfn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtovwdtxjj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gthfpbpzwc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gtayvehums.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtcdaqfhyz.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtmgllewmr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gthjlfnwat.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtkphkzjpt.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtnlhwkfhb.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtdorgsova.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtllpbhrso.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gtcxyafofi.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtueqdezhs.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtieibpfog.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnfkahlco.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtrkhameun.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgaztijeb.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtfhblmqlu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtlveguryr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gttibnjtei.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtzhtlydya.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtpchnvadj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtmcfoiwhe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtqzcprpry.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gtihmhuzef.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtiayzeoyr.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gtbhsftgyh.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtqnssiqgj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtljmhmhet.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtwsgluwum.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtophpmmay.html

Java: "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtgdcealnf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtfjkwpeyy.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtmusjwgsf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtmeceekui.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gttdomzmxq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtulowjprl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gturcbddst.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gthpoafjio.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtjcyzrvgx.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtikhdbfxk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtnjqyxtyx.html


<!-- 参考信息 -->