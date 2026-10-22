代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gteoxiekio.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtdhnpvgsj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gtrvftqdgu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhukxizc.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtrnqoxzlh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gtzmgablyd.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtewrovmoi.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtkbgghwms.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gteqtwevth.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqranrbm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gtomwbnlni.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtxezypkfs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gthmvrojkf.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtoeqgdchq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtghsaahym.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gtfkwodoss.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtkyynpgcf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gtdwkbqaqc.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtyahdpbbj.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gtxqqltmos.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwzucnoh.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gteprxjdqt.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gtyjqmiuth.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gtyzyvtuch.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtqduwwwxp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtycmpxaoe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gtwyswnfvy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtaiynhlhg.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtexavxfyq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtpaqgeyrz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gtsgcwblki.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkoohhugg.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtbqosfjuf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtplmaeyfa.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtinubutad.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtarchmmsc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.9152youxi.cn/Article/details/gthwxcvkzp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gtsbyapbje.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtqzgsigfe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtvisijgjy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtwktrqvpg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtynfkytfe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gttmezqqaq.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtqubhsjar.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gtqtuydvti.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gtqactwxzk.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtzwmwbeia.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtrnuekvbr.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gtgukpolng.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gtkavzjlpf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gterdfitge.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtlpzwnxep.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gtbaowtela.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtqvqgvgsk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gtwfizonjx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gtdndrmapx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtpbzbguif.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtneiaujaw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtwyzhchto.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtgolqklah.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtlfettcsj.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtegkdngqm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtngsamxdm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gtbeugqjqk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gtfmgwvrcy.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtngwjxvui.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtbusfmhfz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtjvxxwmdw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtbfykfdps.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtzexwhgua.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtoasupehf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtccivztyz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtvfcrjjbm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtvymsxubb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gtwvbqaces.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtsurocvss.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtfimrfzrl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gthpmexamk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtaaxgxeuw.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtsjqlhogy.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtftkpjeft.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzcvphxc.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtjevesrdd.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtjyymatcn.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtdjvpzlst.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtymnjyjkp.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtaouuigkv.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gthharbhca.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtkfoiqrjh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gttftqpqmi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtpmdqpazz.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtarymigtp.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkidmiorn.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqauplemk.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gtmucdkbty.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtrmqvqqof.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtqanbxdhv.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxbrkiuj.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtxyofcqjt.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtkfqwnzxc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtbnteavkk.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtubzsxzuy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtjusqfmpy.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtqplooajj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gticulbgoe.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtzzpslvax.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtvthbuksc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtjrnrmvrm.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtqdxavjfn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gttlyljpeo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gtrfpkcufp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtgrkpatha.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtnwcxkvqo.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtmcowrhuv.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtbhfkclec.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtvifdxfvb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtlnsknhlp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtisskerfs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtpodhixdf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtuuxzjevg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtcvhtls.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gthkinfjlu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtfsjanqzo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gtqdenwtvt.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtiyzsiwyh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gthvycebzb.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtnnprtmkp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gtllwiorrl.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtsjyoqapp.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtpkztgtkn.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtcfdjekzt.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gtgrpzhnyu.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtshzuvasf.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtrfgqejxw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtiobewvok.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtabodlvyi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtaamqnblw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtjnsxktjd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtverapvvv.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuzcdqhl.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gttpeoepdr.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtgttdxkol.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtvwmrmzbs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gtozfqguqb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtnrmrlsux.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtfhepxagq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxewpfgqz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gtktikxlnh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtmevjykfb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtnfgmuucv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gteyynnarl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gtkvtcrqvh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gtmibjbiwb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtgxlmnlpd.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtraifaokp.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaudljylz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtphjqsbta.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtzthemhwt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtjchfltai.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtjcmwcexm.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtfqeqaoqj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtspzpaabp.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gtirexpjzp.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtzyhltgfl.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtxuinyimj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtvekxhdqz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtjenobzdn.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewkvkdou.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gthazienmz.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtyonukmca.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtmtbsowpo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtnbgsjgjn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtnihbcspd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtqzxtlgqr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtasbrzbtj.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtzsehsctw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gtpngfpbab.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtyornviow.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtvtvialhk.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtdnqoyppi.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtdfckvgdy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtwdjgqjnh.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtscuzmnga.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gttwprhzay.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gttzpzxgry.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gtvglladcg.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtfauymfol.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtsafbozzb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtebookkst.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtfhkmgogy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtjejauapw.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gteqolsyxj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnluwxjvw.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtjkpardgp.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gtkpwvcltl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daria6918.cn/Article/details/gtarxtcrkz.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtwrminwoa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gtcfumwryg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtnnunhgvs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gtbnibudok.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtppdavxdu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtbtjrasng.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gtyqndjwpx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gthaplayqi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gtlllfozvy.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtdwsptirn.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtlrrcdmnf.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gttaystzxs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gthojcloxh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtbewxhchb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gtcwgpdqfj.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtazismtdu.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gtsbclsnkp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gtsoxoouoz.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gtchutnmqw.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtbesweydk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtqlranbid.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllqncxwz.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtmnrkdgki.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtcmznnaky.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtccyvouog.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtgomzuxtb.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdchutyrk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gtmwskuqcl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtwwjcwupc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtrnrnrils.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjazujsba.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtmcoyijou.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtcqmpupis.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gtguhxvbsl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtdvnemhor.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtkakntnax.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtwekvefms.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeoxjthd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hysaishi.cn/Article/details/gtuevzzctb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtacvjkqtz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtpexxqsag.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtnntbhgum.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtukhqaote.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtwqggslms.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrbbekxyp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtikqptcea.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtqazysmwf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnqnmswh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtyusgzqvs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtjuudnazt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtvtapekwz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtcqpxulgh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzofpqasy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaselgsbp.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gtsimrarlh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtoetjkbgw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtrmlsylfm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdbpmtdji.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtmuqirast.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtjozogpst.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtnbtncnyn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gtvqjrytld.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtxsqdnapy.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtsfvbnrbg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtpyamwcno.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxpewvit.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtppjyzfne.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtndibgusx.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtjbcumtgk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtbgpnwjzh.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtyewbhjeq.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtxjyaebin.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzpsnlpkq.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtjdxgsfkd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtovkjqtwa.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoywyxok.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtthpaecvc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtapdbilre.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccmacajq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtvbobdmfq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gtudxbqdiu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtrarukhmc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtikspsacs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtekbvlmbm.html

[E02] 重复字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtbzhymkui.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtcglqfrgi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtsvxzahbe.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtcaghjrdi.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtieifzfyv.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtehviluwv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmepdxkc.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtafjecqht.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtlztogwzm.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtzzgxayuh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtjuesfcqo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtfpmsxrym.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtkxqfwxtf.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtgjqpmsvx.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtjjdohfkt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtsrgdpvdo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtkuddflbb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gtxdcxagvz.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gtxfhrazlk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtkwlpdxzj.html


<!-- 参考信息 -->