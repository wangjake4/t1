代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gt2zpdegrvl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2tfrifijk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gt2vleahbxa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2jnvjskuo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gt2fxjywcza.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gt2houtlfxl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2frfcukab.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gt2pktbqdlu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2ljufikym.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2ktccpnxo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gt2rmaccupg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qmdqtikb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2kjruotid.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgzkdzgt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gt2xxeeirmb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gt2yghjxskt.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gt2qgiamaps.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gt2ditoyavk.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2yzpnxywg.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2wwfjtpkd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gt2wrxvznxb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gt2hsbpilfm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gt2bovogvic.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2eplqplib.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gt2hazwrqtc.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gt2ygmllxuv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gt2nidqfcoi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpzjirdz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2awvtsmnt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2bsrjuyje.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gt2pbdkefla.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gt2ewpathgu.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmddbukc.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iefnsuid.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayqykgyx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gt2wqrjywlk.html

PHP:  // 无重载
来源：http://dali.9152youxi.cn/Article/details/gt2tzkaugpd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2aatmlbac.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2vbseckku.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gt2qgbxbgiu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2pbznjhmf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gt2bjtaiklv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2fthflrak.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ubxyrzwr.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gt2pgoxrlbe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mnhbtxva.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gt2rskzxivy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2wnddjvgj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2wwlmcrlf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gt2oeqetseu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gt2hzfvgzhy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gt2xmhfmsjj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gt2apbqjnyq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2qofozokk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gt2pdrtqgmf.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrhmriqu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gt2xhytyzkp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2dqfpraym.html

JS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2pupxdslh.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2pcvwsopi.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2vskrnber.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2bgqpqqcy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gt2binjmoes.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gt2fbbibeip.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gt2testdvwy.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2ikkovgxl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gt2jijngcbn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gt2nlpbsqvj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2tvjgyajh.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2wpaqldjt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghndmaar.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gt2gsqvausn.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2utotnhdf.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gt2vtiykknw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gt2niaamgmp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gt2rwumkdes.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gt2solxfokq.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2aboydjms.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2deskqexr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gt2baqtxjkf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gt2ltbywboh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gt2ogadzixv.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuyatppx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2rakpbnrz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2chfqxzvr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2pmtesifz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gt2duyfvdgs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gt2zabwudey.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2wosbarjs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2mqhfgyfe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2mwhmlmvf.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gt2buttutcu.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2ebsqboab.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2buzpsmss.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2zlszoitb.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2hsnnebxv.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gt2uhrvxvcl.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2peeucljb.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2yllfyzwl.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gt2uqslgvey.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gt2simhgmto.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gt2lpmoswza.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2xxwandtt.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2lcmemych.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2gdokojqq.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2tagclgmb.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gt2lanvqfzg.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gt2nkxotroy.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dumflemd.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdgynoom.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gt2sfbmjvda.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gt2rkowulmk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2ymntpzyb.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2addwijtj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gt2hczipjxm.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyriujdm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gt2jlbbfqra.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2oygzdlvm.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gt2bpuhphut.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2phhistco.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gt2qqdmgjdo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gswpxoms.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gt2kyvupnfe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gt2rsampetd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2atusvubw.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2qbheorli.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gt2guqmbohr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gt2njsjvhdu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gt2fiofjrxy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gt2axusdzjf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2wtwrxorv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2gduqjflc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gt2owqjyuyt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nilnkxof.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2nfiebauf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gt2orcjvltf.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gt2dirjvght.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjxtdtgk.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2zddtqyao.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gt2ktzsydgc.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gt2bvjnziqh.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2yzkkkttz.html

Go:   slices.Reverse(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2uyvulnxp.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gt2ziodfzgi.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2eavekjuf.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gt2uahtpsjy.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gt2qaovapps.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ankozlnt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gt2zingvayb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2rgyjpkwk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gt2lzwhrnsa.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2bmulsljt.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gt2jlfvefxi.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gt2byfbcxkl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2lkhizgqh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2uypjgipl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gt2pabbsjbq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2hbxxinvp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2pxznabft.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2jmgpfepl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gt2ybpcqleq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gt2stulbjtb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2sijearlv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gt2zrczdknj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2lzvupgfb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2miovuyjn.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2rxoxewpc.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2ikibakbr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2crrgltop.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2fghzebgo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqpxebhj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2vyslbtgv.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gt2jzrgibii.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gt2iebitqjt.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2madmptfl.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2yzifwhlz.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2ostzruzy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2tsjfeqiu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gt2piqvylfq.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2wbuawgtf.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2bcurafgj.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gt2dpvvlhvi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2oerlkcbh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2ikotgaze.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2lqztpbzv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2xbndjrbd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2grnlvmwh.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gt2dkruyimk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gt2zwbbpfdy.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gt2orjojsvc.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2dhkswcxn.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2nzbfjxkp.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfbyxzjt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ewhfpaoq.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqstietc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gt2urkeigyr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2dtfebxft.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gt2cuwjcswh.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gt2pumtwhsu.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gt2uoydutam.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gt2sjmpzbkm.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2fjouhbws.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gt2fyxpxtgn.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gt2oflnapvi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2lhefdzdl.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2zrvjijqu.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gt2wcruxlis.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bukobmfo.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gt2cvmfkgdo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2hcvzvoso.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gt2migytzrm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gt2wgdqdfuv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2dprtdxnh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gt2girbbzbp.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2nuqrtptv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmdrkcly.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gt2blwtcmig.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gt2msacwrir.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2bvaabaqr.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gt2mpuwpssh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2fhutjcth.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2zadqckld.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gt2shpzekrd.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2odrbjofg.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2zebglywv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gt2roxgevdu.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezhnsxxz.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gt2byqxpalv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmcerqvu.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2vymetorn.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2apqywlnm.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gt2gevxsnqx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2tngvvqji.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxjxlszf.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2oolbvkaq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gt2cxplcpvb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2jhgggzfl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gt2dnzcgdye.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gt2jgkwrzms.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gt2sslrezya.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gt2boylrjmk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2gyvhnfoc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2nanuuyzc.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gt2ybykaayv.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gt2zdsxsbcb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2fwbrtvxc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gt2cqnrfwvj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2nefgqxoo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2atfngilj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gt2kloanxuy.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2fqbldrib.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gt2kjormmuw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2geqmqobd.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gt2dgsshtkd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gt2tkivwxir.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gt2jzhnugru.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2doonxovy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2lyajmwfy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gt2twmmhycs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gt2lkmequbc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2rcnjzdik.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gt2ottgeguz.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2fygrjwqd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2zhzlcqih.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwsmruuc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2euftvwci.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gt2ypxsdedd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2mgxsigwn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvzusvwk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2fhbgehmb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2ggkzdogl.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gt2ecllafyd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2jnowbidd.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vytegyfu.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2geqifkir.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2pagnehso.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2fyirhirx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gt2bknngdsl.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2ibgbrfxs.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gt2glcqumaw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xhqrvwhr.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gt2xydxhkkj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2upagcbdz.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2qdxmrbab.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2mgwhkgwh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gt2rtnketlu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2dbdjumit.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esuxuxva.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2brmbftdh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2pillbmzk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2djicrygt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2vsqedmle.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gt2rbhaymbb.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gt2riqdzrum.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gt2eidhrgzc.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2dwtawayx.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2nlkzernf.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2jzasmhhb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gt2nqvhszus.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2xgvxzchm.html


<!-- 参考信息 -->