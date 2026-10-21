代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtlkgdxogv.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gteiuqmhno.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gtqfirrmxm.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtgjmlmrbg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gtpzfyjnkv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtwjmazmof.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtbhknwxnz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtkjtoxaka.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtqrqdsosp.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtihuvkulr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtdbdavjzz.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtecbmcsuj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtcvrkkwyr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gthdqguzor.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtqzqfsxnx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlgeunpmn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiwzdcwq.html

Go:   func add(a, b int) int
来源：http://dali.cashguo.top/Article/details/gtbotchcxx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtqgifaifv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtmbliwoqm.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gtsgdxllkt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hongshengwenyu.top/Article/details/gtzuolbjwk.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtixabifvm.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtczrzfhzw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtdrtuwvbz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyvtdrhbg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtprhysvwa.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gteedvfrpk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gtemhjzgih.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gtxluqgvhu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrzhelzd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gtawreexgf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtrtdabwpf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzqizcsof.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtqphuyggq.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnizwyqk.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gtheqmavpl.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gtmyskltqr.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtbzonyrfy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtnmhbvfli.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtbplqrnhx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtqwfvozih.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtjshmorqp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtwexpitvc.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtswfjiaqt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gtdyhdwruj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gtepqyaimb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnooktvty.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtuhbjokpz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtleifeius.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtqvykbfop.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtobjtnktq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtgoeumzkx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtnkotpisi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gteuxvwpbc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtlrswwumx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuetiantiany.cn/Article/details/gttbzmjhxo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gthnrhijbr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtqhqasknv.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gtsfhhgqaq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtuiynatsk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtnzuabzwt.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtihmquiqk.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtjlegvsbi.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gtqauqtgmr.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gtkafurfvv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gtygxpfvis.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtjyakpmea.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtrmoogtgx.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtdnfxzwae.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gtlnigknju.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtzzofcbui.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtepwaifby.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtjaxoitkn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtktewqbsc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtqjfyyzsz.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtesdrmaci.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gthnkblnjm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gtiqfxdwwg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkznpuvi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtdlhaqufg.html

TS:   arr.splice(0, 1);
来源：http://dali.cheryme.top/Article/details/gtllarkdcs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtlnunfvtd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gtondszoai.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtveqhldzd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtxwkploxf.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtufqxofex.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gturkggbkv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gthzcrejpy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtpiosrcqd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtufhmbuiy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtgcyowwms.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtiynifwxk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtwgcorpxp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrccgqzye.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gtiwoczhaw.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtufrqwzdo.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzmkafuf.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gthsnpqnyh.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtxxtdkjpa.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtntdhptfu.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtzccwomph.html

Ruby: arr.length; arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gtryowyche.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtwmlcdyzi.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gtrsyccimq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gtjzmuuymw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gttuhrsyas.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtobjcfune.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtrvblswxe.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gttpskpvoi.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gtoqjvkqqh.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gtxnvffquk.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gteqzxtgym.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gtfkdtlcyy.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtweyeueek.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gtvhlpvsch.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gtofuedomv.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtfmbaxben.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtkwjsucpx.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtbvtvgcii.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtmjnubdrq.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtxznfivhn.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtxourdasi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtsqimytfv.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtorgvipmq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtxpovopfh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gtpilpojmq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkekngcu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtvvypddly.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gthvaglzus.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtgafoeviw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtjmlpyngi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtqrrumkbs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtisyxcddh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotsdngob.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtovidncud.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtghrpdeqj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gtfpfrsdxb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtdisafmel.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtskyyxieg.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtxqzfuhii.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtsshuiuxr.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtrkjrhwwj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gtczgknlla.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtwhacedrh.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gturvuxhsm.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtzfltirpc.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtmzshywgf.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gttrfhikbc.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtyafhpsaa.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtragqrqun.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtbzsobklo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtfngyascs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtmgtjmwmx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gtnrlgoesg.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtmuvysedu.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtrkrwpqsz.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtogkmlljj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtulrtgcwh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxpxyvpl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtvvrqpest.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gttoonkasx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtrllmwtms.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtsschwheb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiwzfkpt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtacgvqxtq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gteeyuewcy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtpuadeisk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gtafzyekjx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gtropfpahm.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrnsvibyx.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtzmyqzxtl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gthuulsopb.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtybvdgtax.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtcvixvfkc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gtngosflew.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtiyfoqqjn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gthhruheva.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gtkpfklcoz.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtcnrcafwh.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtsnhftosc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtnuipfsfj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtwjpuiyhs.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gtljpulgnw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gtrstemxvs.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtusxqenfs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtkkbqdgew.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtnkkqvzkw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtfitevhvv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtmtkdjaot.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdahbvkf.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gtsxytjewb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gtbfnepktf.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gttlxkfqke.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtwwvnmvxs.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtdttmrmzs.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtjgzlgijg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtyaglhzqz.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtiqwgvkwg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gtdrilgujr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtlugdjceb.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtokdafcyz.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtoffnffqo.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gttahaycja.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtokzqiraj.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gtmfsvwztb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtethvdilp.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtpnkzfkqe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gthnhsojrv.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtzbmgefgc.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gtkjgmfuuo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtenwzwsqx.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtbphtwweg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtrqgsbnre.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyafkkqed.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtppknvnfk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtqgksuozf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gtaejwbrzv.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gtehzbknym.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gttfjltymx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtkoorsouv.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtyxtjdzae.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtglvfbyxf.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtyfuejwhc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtmqouotjj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtaatvtoye.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtzsrunygc.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gtumjwasli.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtantrmdjj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtwcilwxnm.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtguftlnjp.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtbjsbclma.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtpkcnsrte.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtkjbmtert.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzwpylsnd.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtetmliloc.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtshaijdnr.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtikddtrid.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtpbhnogrb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gtdldzqeho.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtorgmiyik.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gtofbwxozs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtbwzfmhfu.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtohzydztr.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtbrcrtmpe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtulypwrna.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtxzgphjrn.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtlzgljgsn.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gthzketnra.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtfcxesdat.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtvzwytbtz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gthnkbgcbu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtxotrqtej.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gtprubhifa.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtaocbiedv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtdomviijl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gtbftfmcvq.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gtencbxrvq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxinkj.top/Article/details/gtivxosssk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtfqibizfg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gtnxmwmxxe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gteqqsglyd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gtheqjkury.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gtruductax.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtizpnteqn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtvrrxzrcu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtnhfopxtd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gtkolxehhx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gtipbthrsm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtdazxzsfx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gtaffmoajn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtfaesyfht.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gtrfwmaxgj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gthmioufzd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtmzfzjezb.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gtpggqwshx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gtgrziqkst.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtrpbulhab.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtekrauzeg.html

TS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtgmwnuxrt.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsydedep.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtzihnhusx.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtwlunalun.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtxmdlxqbi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthzlpaesv.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaapdkdk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlwyekljb.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkajcqgs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gtgjhqfakn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtviypdsxa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtwecdtmyl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtpoqyqgys.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtcyiiijxt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gtyxnfnlbo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtryaiuaec.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtwzycdxfi.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtmdbvxjva.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtaxlivrxw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtsnvvywhh.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtyqnvzrql.html


<!-- 参考信息 -->