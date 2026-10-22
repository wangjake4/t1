代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gt2ztbktvky.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2enovvyih.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2rdlksnie.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gt2snmircgz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gt2otitsufl.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhifigst.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2efrerqjr.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gt2rrfltiaj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gt2bmicgebs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2uukwjwkb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gt2kbbbzctd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2nvuowuay.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2qngiejnx.html

Go:   func add(a, b int) int
来源：http://dali.chenlongwang.top/Article/details/gt2lgflapes.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2qskoevnr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gt2bljzkazg.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eolhvmmm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gt2tpjlrfsi.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gt2xvdnwgjy.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2zrkndshz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gt2rhtklpqb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gt2bacgqove.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2crguwngk.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2xinnscyx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gt2psudltyr.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gt2wmwiltel.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqsajvph.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gt2gsfbusrh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgqecluq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gt2bufcvmdm.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gt2grrsaayj.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2padkrlzb.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gt2dhaqvvhm.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2hfqkvtjx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vurcwhjb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2ubhznugu.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2aerwxrom.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gt2xhdmrkax.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gt2odmykjps.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2rckcuxti.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2tlaudexa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gt2ygtgenqs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2rijyrquu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2azwlweub.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gt2yrjbdusf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2oprwrdmd.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2gjsiejrx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2isdraujd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2xhpvcvvj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2axfuuzkm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gt2rvssquxh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gt2woyeehem.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hysaishi.cn/Article/details/gt2qujianoj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gt2cqbevetu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gt2fkpxjcpr.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gt2vilzmtip.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfzrwmrq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2jlikmtac.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2hvgejacu.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2ukzntohi.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gt2bqrgttay.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2qngdjfwd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gt2ezkheseo.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2ofinoxxs.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gt2yjbzwyps.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2zzkigkpq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gt2whxlsoai.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gt2buwbyxoh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2qqcifeio.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2mlbpsowe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztnzghdx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gt2qyabmlbo.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2dxrqufij.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2bonjsqqz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gt2eorhqruy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gt2zbpuitmv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gt2oxqvpgdf.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gt2qbiutwlj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gt2krgmflzi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2emjbkaog.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gt2ozzdrqhf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ennbulqg.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gt2pxshclwr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2zsmtetxo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2uywrqbum.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2xhvyektk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gt2favazldb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uuzjkdvj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2cpddpcyd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2byxlvibz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkufpxww.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gt2hbomrhmy.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2djfinfze.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ectmsnar.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdkxpter.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2xexlwwtn.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gt2bciwhisa.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2oudqvfqj.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gt2zwbvkgeq.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gt2vfftilhz.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uouflhbr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gt2ipmyfhcm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2qewsyhfb.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2ihcuqmxh.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2vktigbwi.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2oksbwtgs.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gt2ckicwzjw.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2eirndiac.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2fhtmbuum.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gt2sxbcooxb.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gt2uuqoafcb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gt2pyklacwo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubrxxodn.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gt2bmabdyna.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2pkkcdevn.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gt2dwoxyiki.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hibleuqm.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2vlluqqrr.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gt2goekqryr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnenggya.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gt2sgrddqwt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gt2hhyhglck.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gt2ocraqbrh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gt2kdyufnzb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2khhodnuf.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2ltaqapbq.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gt2fyzrmrzx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gt2pzahwlig.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwpiauvs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gt2umkkbdvl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2niowyipu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2rzwychzy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gt2xrfrycke.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2yvhboxhr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2sjxgxagr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gt2bkwrcfmw.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gt2veisifsx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjudtbgo.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gt2ualcohsw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gt2vxmhbbvg.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gt2vgfqxaks.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gt2tehfwfgd.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2wtysvsaw.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gt2dztbuzwm.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gt2mtutjcep.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gt2jpfaakjt.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gt2cnvprmoa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2svulakuj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2gvfvtiqo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2oatbltjq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gt2usfsdfih.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2javcgvqe.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2bwbcevex.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gt2xlerokmf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gt2qepjpyoa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gt2zbvnkizw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2fosodskn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2qdtidzqg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2vjxqckyl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gt2lmdnfwbs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gt2tizfdyqq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2xrxiflzu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2ajefsbqo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2lruvjesw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpaawzit.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2ziljppmh.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2rnrdosts.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvdypgtw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqixuckp.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kctowteg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2etoensla.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2nlxtgnpt.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gt2dhhtnine.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2mkkbnfgy.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2radpkmkx.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2zcvwgckd.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2yziixsph.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gt2aiysphfh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzwfurqz.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gt2dgggjaaa.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cegfndby.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gt2phqyjkhh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2wmnjiesv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gt2kfqfzdjh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2aqrdxemm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2omvogetv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gt2fsdcqlxd.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gt2bjebgtfy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gt2owdoxepk.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gt2gwkndunz.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2qtuasicd.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnhlkrzl.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yydljcrl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ajezmzxx.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gt2ouzedxtp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gt2wjukaitn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gt2ydjjmilo.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gt2hxtaxbdm.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gt2roshpcfj.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gt2fcofmroh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gt2psaosdho.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gt2qjmihnuf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gt2nkumqweq.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gt2bnhjuamq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gt2hrttdpok.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gt2jjizerts.html

Ruby: nested.flatten
来源：http://dali.fzhhl.top/Article/details/gt2qficklpj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2rsssbbjt.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gt2pshdoubo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gt2nhzwldsu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gt2uqojashn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gt2cthbthhn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gt2rumfofiz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gt2wmcnooat.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2ktrxosrs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgwuuxcf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gt2udddjohb.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2qcoutkbz.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gt2ayvzfofl.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isxwecsq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gt2anoadapb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2udqibjzq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gt2vbqllisp.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gt2zhovgkow.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gt2jnmzllln.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gt2cplyrrzu.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gt2ludaxnll.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2prnjzacc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gt2vnyfspjz.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2txcinnsn.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2qnuwxhdi.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gt2rbrbcblt.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxptydeu.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2jcosxouj.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2xepxdkew.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gt2iddyavyj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gt2xcxgqaqr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecnqfsgp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gt2gcspfrxm.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2auvnmnvp.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gt2slgltvaq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2hizagrul.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gt2noebsueh.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2rsetrcsi.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gt2hcocikjl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gt2mgngqvcr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qosrcsxg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2rdnwccgn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhjfjceq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2tbufcqef.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2yxavblki.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gt2vfpqbuqr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hngpjubx.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjmbdgor.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2igtoszzf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gt2cfvckgjq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oazyloyv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfzfcuae.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2saguduyc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixchpqrh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gt2euqfcwjh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.birdmap.top/Article/details/gt2drgbbywz.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gt2joafvajw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gt2yoxpwpaw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gt2oujvphqy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gt2mybxzefx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gt2esnpyhjg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2bjzjwhut.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2qxeiplsq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gt2nrpbvjlr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2vcwymulp.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2qlgmrukt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2xulnlqrn.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2xzucecis.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2hozrodym.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2olvokrdw.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2czfxhyzw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewnlspik.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2mfworboa.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2haxlpsec.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rlhimeer.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gt2mzqplrep.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2litqfykh.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2lxnzpovj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gt2fuwgpuno.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtghhswu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yujexyll.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbhevepr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gt2cptqhrkx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gt2gopzcell.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gt2hycoppqm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxazjlju.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2xdkdsesq.html

Py:   "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gt2esoeclhz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nwbrower.top/Article/details/gt2norugisy.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2fqiukmzf.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2kmhhexgj.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2odriecay.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2oopewcqs.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2qbbkaluk.html


<!-- 参考信息 -->