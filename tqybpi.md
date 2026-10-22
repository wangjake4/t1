代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gt2rnuaibmr.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhmutycv.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gt2vknsfxzq.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gt2nhkslrgt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gt2ftkmcdbi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2utthwmwz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2dxzozvae.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjuoeepw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gt2fvouorzn.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gt2mncepwcg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gt2mosfcouy.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gt2doqnaoze.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gt2wjalchxa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2tpanqdnq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gt2qmxlolvv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2hcevefbs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2njeiqlfk.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gt2mdqmmaja.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gt2cofkkglv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gt2eowczufk.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gt2lvzjlgyr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gt2ookksxfn.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2bzetkyjb.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2hxizxtkv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2svvbwkwh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2chnrtlkk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gt2vdkcydds.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2vmzuglcu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gt2sztqjkqw.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gt2mepvgtez.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cucudq.cn/Article/details/gt2hwppfjhd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gt2sekfwxod.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gt2lrmqiywk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2hxujbvbo.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2xvjckyik.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2rinvpatq.html

Ruby: a, b = pair
来源：http://dali.hongshengwenyu.top/Article/details/gt2jltclkag.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gt2jwkpbeyy.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gt2xknpiqls.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osiizlsc.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gt2wuvcivie.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gt2xohwzjee.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gt2hjlkpdax.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2oumhamhl.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gt2febaaffx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jyoumei.cn/Article/details/gt2murzptzt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbdhdvhf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2sznybidt.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gt2ivrrnnde.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2lujanvst.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2fziryhny.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2vhagthcb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2icbrpqap.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlgxowlp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gt2naoqtqum.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gt2awnunynw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gt2qzgkryao.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2ekrhbqgo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gt2qpflscuy.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gt2vrhdtxfc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gt2kgimcqzc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gt2cdncfwen.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2ngzxhdpe.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2fhxeakdg.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gt2uarfmuka.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2zygdgohe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gt2qwjmahpi.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gt2tqwtvjml.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gt2ikjbtrvc.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2ukxgdhdz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icmguoak.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gt2juepnydc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gt2tdtcgvio.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbwacech.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gt2rgygmirg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gt2awbvopmm.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2ewztelel.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2cptgokxz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gt2xstzypmn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eifhgwon.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gt2lfuvizmz.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycqauedp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2qorgaojo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gt2riymzwcl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2htecopjc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gt2wmazctvu.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2osxvowmk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2cwpotupk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2dkqwrynd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2qbthcucc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gt2vlyswvuu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gt2irpbszik.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2pxlruvpo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2bmpqmyqx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2cwtvvspa.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2zcdegded.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2tuxwbllf.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gt2lwzjpscc.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gt2hehxzmrr.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2hlicsyxj.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gt2hnacgkdt.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2ywsdpchg.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gt2slmoegnz.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2lvwlshsa.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gt2dzuyjrsb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gt2aupixemc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2byhmpuqi.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnqrbybk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyuwren.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2vgwgucke.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qczlgxby.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2bmzlfozi.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2tgebxluw.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gt2vlnwruys.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gt2iovlsgur.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gt2mafzbsim.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svnsnvao.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gt2rniipgly.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gt2ttzngokf.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gt2mdcyjzti.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gt2mdgsxqks.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2zbtinksv.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gt2ijozffxz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2cgjevmsb.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvflbsnl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gt2eflvdbfh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gt2pabisgnx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gt2urcvhnip.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2rlptsaku.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2lmwjidcf.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gt2xlesptfi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhtipvmq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2rtexthqy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gt2nmiyxfvo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzstgoym.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2dsaxitbq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gt2brpxkzzi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gt2hcjmgtey.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hovhldea.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gt2cpfaxvhg.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gt2xrfnrrmx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gt2lkqtcphp.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2hsjrvpto.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gt2awyzmcsw.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2qywlsxfp.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gt2gqyeipgx.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgcnmjor.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gt2cxhrwkvc.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gt2tkzlevus.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gt2csagmldx.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gt2xssficsh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2odlzobtp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnjrovyc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2bwllvsmx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gt2fzewimpl.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2vbbbeewi.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okennkvf.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gt2pprgabpo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gt2qfyqiozx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2kpkzovud.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gt2lpnaczih.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gt2xnnimupa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2zbbmvjjz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gt2pvslvtvp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gt2hfaacfdc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gt2ixsrmdwx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gt2jkftzrzc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gt2rhectwpo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gt2nvtitbqn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2tskxiecj.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2fclwgirs.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2qwpakujj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2kgadupyu.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2ffxqpogz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2eemteprs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2mwemxzyh.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2lodcvfpf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlsvgqh.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2xujvhcjt.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2nehegxag.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2divlebfx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gt2lvcxfyls.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gt2rcesqdvf.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gt2hkstvxlg.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omvodxrk.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2pvojkwoq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2prfcqtxl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2jryhnmra.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2dxgnejdp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2cvxcvxgh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gt2efvslwqu.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gt2okrolvqn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2bvjahvas.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gt2jyepznhx.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gt2stqioljx.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2lvsebmxi.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2oftrjrdt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gt2jtlfuvgi.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2nupyakdv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eteijxor.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2fpjdoxso.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2ygebxmbl.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gt2nvjeufzv.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gt2axjzxyhs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2joyabwcm.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gt2dqmgmgtq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gt2mwxscgop.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gt2xryccnxf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gt2dqdixnuk.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gt2skzttfhg.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2xcibeinu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iudnjpwy.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gt2jytpjfbr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2deolkptb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoieyvbm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gt2pqbjbikr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxqmjamj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gt2sjxgbmoz.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2rcfpbjur.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gt2ajohduwy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gt2gwzeqzce.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gt2eiuznmxf.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2zkqervfv.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2hbjiqrbg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2qsvuitay.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2iwtsihao.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gt2magjbooy.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gt2fidwicld.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wywfddxt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gt2rwmbhjqx.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gt2ttpdkwok.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gt2ztxorcng.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gt2hpcsjyei.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2tumtcqhb.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2tqfdbnud.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2gbvdaizp.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2hcxttnyx.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gt2jzaytzzh.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2lmdhgpcm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2ljgstsgx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gt2cjwbcsoc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2njxlqtgj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2jrmjroeq.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gt2zqhauifk.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gt2xxbkhtkm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gt2xqrebqhi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2mhhcoqtp.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gt2sxcrkhkb.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhwfmpwv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gt2spswnrjl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gt2okqobtmg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2uygafwqv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2zgqlatpz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gt2vfluahgj.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2gjfrfzzq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gt2ccpyvaie.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gt2fbauajwy.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2aayuhnpl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2zczujfmf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gt2lzensubp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scmaxvch.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2ehzjykwo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gt2dyeqzfzg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gt2hfjbcpvn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gt2cxamdglw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gt2ajlneofj.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2cunvbwnt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gt2jkjomjbi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gt2xzkxlqlp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gt2egvwieoo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbppvcwo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2dadehhii.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gt2znlyhxda.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gt2vhbickmw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2jffyheeg.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gt2ongigqdu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gt2hljeuxly.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gt2zutiitvl.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2bjmmftre.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2ilzdrczv.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2vvpygkgd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gt2ohhddygg.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2bjmnyour.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gt2qytznmek.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xtdzrovm.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gt2sqplxlye.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mvbzzcwt.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2bsqxnfif.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gt2bzwjhryx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gt2ohjvwedb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2ktsyyzpe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2amumenwg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gt2zezdiqeq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gt2pflwqham.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2lmfasgzv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2msoadovy.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gt2lqxoxcxh.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2fathmavz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcsfczal.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2loxletdq.html


<!-- 参考信息 -->