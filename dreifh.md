代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gt2ttogvvzg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsuognu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2kdjyhkwv.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gt2ponslqps.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2eeqpovqb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2nneqsjsy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gt2kcmtdujs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zacacwua.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2hreizoqq.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gt2ckdnjtma.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gt2bqbgryka.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gt2lzypsehj.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gt2wzdfiiyq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gt2ztsbvpvt.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbqihquc.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2keqptdhp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xprhxdfv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gt2cvwdjwxu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gt2tokbefxs.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2hoyqyyus.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qeszgkan.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cstvtskf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gt2gqcugolr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2wmbwmkii.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwnhafkn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvlfkrnm.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2owrmveto.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gt2btsubjgi.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gt2vvjwntpj.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gt2bmgtyqge.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gt2aiodgomy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2giwbsgau.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gt2rbmzvcmg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gt2tidysger.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gt2psbfzjhl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2hdaezqym.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gt2vymwumkf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gt2lqacohyl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2nzzewnap.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2czhkowds.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gt2lakgblcs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2hsifuisc.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gt2ghmrtzbm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gt2qisvvxxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2scxliife.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2listnezi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gt2eunltgon.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxuanxn.top/Article/details/gt2tjqxncum.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2gifbcjkb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gt2ueqlzllp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvnimwdm.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gt2gqhotmra.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gt2cytqjwzf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gt2ylramwfq.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2biujuwco.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gt2wgbhiwlj.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gt2vggtcwuf.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2soqxpqxv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gt2nuaejayi.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gt2qpzmgcog.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gt2cjndcgrb.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2msyfyckm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbzdhnip.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gt2nhsglxyf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gt2xikmbnns.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2baviguhg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gt2ztwzamoo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gt2ghugrffi.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2ftoilamw.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gt2jkkkqzzn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyxbayhn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gt2baprjxrf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daria6918.cn/Article/details/gt2wmywidku.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gt2nbwizbkz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gt2otgzfhzn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gt2yvjwsytq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gt2dkzkmhcp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gt2ucwegrvl.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gt2azskbqog.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2kgaitgsu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2htsqxber.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2rusfdzsv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gt2wasmersw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gt2wzxbbexz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2zpdefkit.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2toojrfcq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2ovqmrwkq.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2iihgzmtv.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2fuiesukp.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gt2bxhenwll.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2tqjooxju.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2wzldtbtj.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psyfmlfu.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2xpufploi.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gt2froaghlw.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gt2eapkonui.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gt2ezjaqkbj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gt2hwhtaavm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2wfvclnxw.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2rlshsyge.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2rnlvcerk.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2vauffcba.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gt2btzwslcs.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2dxayyyvu.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqkdjruu.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gt2sosgmyce.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gt2weopcdgm.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvkrygzc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hiyimgow.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gt2kkrfssic.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gt2yznpqdzn.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2yfpmorpz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gt2qffprfex.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gt2gfxbmqhr.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gt2mdxodemq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gt2elmxwvce.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2jruprzaa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gt2dhmzmrlv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gt2pzcuvarx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gt2ukiqyaub.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2igbflsvj.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnkxhuog.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gt2nsxskfrb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gt2udpdslav.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gt2lepjvmog.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2zipbwleq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2uexdnjgi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2gioemlny.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gt2xczqwcpn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gt2uxoqzbxl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gt2xeeydqmw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gt2mtiftczn.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aufkydxb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gt2ccfbhsoy.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikmnvlzj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gt2fvyasxtu.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2emqfoyue.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gt2xjrrsrhc.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gt2kktnsorm.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2tubagjjb.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxsgggsn.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gt2zcvctqzu.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gt2kllyrobi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gt2rvywssbj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2ewvectcc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2paxccqat.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssexmfew.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2fxbtulwi.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gt2elwcmkuo.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gt2adtujviw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gt2byevibkf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2rrurshxz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gt2quiisgwk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2easudmao.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gt2mtoooxie.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2sebsouty.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gt2asauducy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gt2kdtpirtq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2ujeavena.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gt2tkkjzyqj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gt2qlmhrikn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcbjbaem.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjjrqbtd.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2thohylyo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gt2xzuarccm.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2iopgstfd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2gtbvngsc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2dtxeevqc.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gt2kembaeza.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2bzvbljjg.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2isskvpva.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2xflsfjmh.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2fqsshwtg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yymvuhbf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gt2btjxswvp.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gt2mfbivdsy.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2fkgoqxuo.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gt2xekxrsoh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2shneeuzy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2bwhyevqa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2ameytigm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2ejotukzd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2sqxjieel.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gt2mdpcuhua.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2tbqtzkhp.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gt2sekadusl.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gt2fczpcgsr.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gt2cmuluehq.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gt2zdtqdxgc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gt2esjaygtg.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2egjjrdni.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyklxkad.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gt2mvfktfsu.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gt2onguyfxg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ziwrtsot.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gt2hozqqttt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gt2cugcefcb.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gt2hsloxrrg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2wgkrdzjs.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gt2duwytccw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2ztmaeiof.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gt2etlxvvbd.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gt2frocknea.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gt2vttaksqm.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gt2exifbtqv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gt2fuhdkbgo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gt2gnfhojmi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gt2dwngkcui.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gt2gfrzdwnh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gt2ytqdeemm.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gt2clqerwaw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gt2gwzioqjg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqnlylst.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2xuqdmdct.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yramiyie.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2rpwaecqe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2kbnmhttb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2yfetwcxv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gt2qiulybam.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2ydozgwzl.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gt2bekxlyye.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gt2vnqmwhdb.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2ynslmkwr.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2fyaqplki.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2ppkribkz.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2phxvaubt.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2diiondpx.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2jygdnsnt.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2ifqtahse.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2itvnsllo.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2cuofbgzm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gt2ydroyqdr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiryxjds.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gt2srojrfzd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2npmnkqlu.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gt2jrszoyfg.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2ojpsmmpx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2milccylu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gt2lzdenfik.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2avfsnccf.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2nemdvemg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kglquavx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2pdqamlfz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mznttxet.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2goysdrnw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gt2zhvxirfs.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2getubmwy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gt2evolceso.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gt2korcrfoe.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gt2mhgcagot.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gt2olpkpniq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpvicrpk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2ggrhebnk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2elyohjmj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jyoumei.cn/Article/details/gt2ckevkikt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guowangkeji.top/Article/details/gt2jvkrykyw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2jupmnoin.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2pnibpyup.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gt2fbyskpao.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhengqikj.top/Article/details/gt2betyukap.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gt2kupyuivi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gt2kajjpdhn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gt2eauyfutm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2utjtvldi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gt2mbpvfkwa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gt2pgnlalye.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gt2lgsmpoek.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gt2kuybafln.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gt2vuuxddif.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2liizowgu.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2gtvjwftt.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2dhyqrbrj.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwrtqcpy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gt2neyuqebi.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2tknlmhpt.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhljtafm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2chadxdhu.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gt2zghmeixt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2eywogjmv.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2zretvcln.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gt2obpjclzx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gt2xqtsmbow.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2qtrnmfme.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2emftaarv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gt2samafzln.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2mvehwnav.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gt2fyjxrvua.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2cqeppxsj.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gt2hfiwyhrg.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gt2uuzxfjin.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnrlrili.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2strichoo.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2sitjamwm.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2gwhzzfsl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gt2zpoligph.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gt2qlbqbwfx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gt2fsmfnepj.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzngklla.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gt2sxsogahe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2zghsofvs.html


<!-- 参考信息 -->