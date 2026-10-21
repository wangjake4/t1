代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtzoxnpgiu.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gtzkyvgdsk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtxxofposz.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevnstlqj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtonhursuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpizpuwvw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gthkcugxhy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtricbogif.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtwkhkazjd.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gtslrsfgfm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gtgbtmbndg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtissxfnxr.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtffprrgoe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtllxhagzf.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtfbbywjte.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtupbutxwf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjokgjfb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtwoidzeen.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtyxaxwimg.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtncltlzmd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtxzypfngm.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gtrmkdsdza.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtsoysfhea.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gtjrmuuqcs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtfrqtwlke.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gttmadmswe.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtoorhddhq.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtenkqcked.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtffddxaux.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtnmcgykyh.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtucjnpuvv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtdadvdrif.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gttfgmaefz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtuyubbqdp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqocxyytq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gtjzypusuw.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtukhqhova.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gtnzflmqml.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbezgikpu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnhlfemfw.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gtnwusnyam.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbgegtvrs.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtxlvvwpwv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gtpmphuqie.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtuhznpuxf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtffjvqunu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gtbyfwsmxf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtepqrinya.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtrqjjrlha.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtfnswmuru.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gtenrjrsjj.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutjbrztq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtaiqtrmph.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtnhjqyeld.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtiwdetkad.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtnneklbkm.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtissybopc.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gtlitnfine.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtpgfxlioc.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtbtgapiej.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubatmmlu.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gtnrqkjsek.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtxkrsxrmv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gtflnbbgvq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtawkqvsbz.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtpoohizla.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtffxmlufd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gttjakuxhp.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gthrucrozg.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmtapaic.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtgahmguwx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gtxijqcgsg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtbzamrrfy.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtwdmopmsi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtxrcqdsby.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtcmhberec.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gtedadoher.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtpedizczy.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gthskrntvz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibwyclkt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtjeoydxud.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtnrnzesqn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtdrbekyws.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtrdsnakaz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtyobqutkk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtszmjiccc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtvynrfbjd.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtnhnyhkfr.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmnthojlh.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gtrbmpfheb.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtmewlbhnt.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtknpbfzst.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gteqarhekz.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbibqnzaj.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuhrpfed.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtjkxmuagx.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtwwipzkwd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtrualqtya.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtixhybvoh.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtyygjhlgu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtxhxurpad.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtfumlhjph.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtdsjoecgg.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtiyhdkula.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtnekzyxfh.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtbvexyunx.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtqnejaydg.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtrsxaknfu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtuavriqes.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtnlyneskk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtzlsyuafq.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtriqtkafw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtcjddnoub.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gtpzlwcqxs.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gtxbkktlub.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtivovctkg.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtabttqohw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtmukquhhj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gttldivbpa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtxqhqmsab.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtgcnisxtw.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtuwdxeobb.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gttbztymeu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtyxxfyjmm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtjxnikroc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtvlwmatyl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gttfgvvdpl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmdwqbob.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gtlwgbmptf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtyaeahulu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtrebzdzvb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtgjsfbxqe.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtirsghrmm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258.top/Article/details/gthkggeong.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtzjqxnzcu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtidlpbjot.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtagqicnai.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtphlkywny.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gtaaindjqs.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtnmoeprpe.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtdeyzleqn.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gtdmvliltv.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gtsjubrvdq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtzbrqmqod.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gthdlspgig.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtfzuafghx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtonesyfuw.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqdjudfg.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gtknggzhws.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtwnjikcfi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gtytkhlmss.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtlappslwv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gteauxqxdk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtiigcjxtw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtiwcguudu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtaodxskfx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gtojcxmpbh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gtmlndxyel.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtkqaidrbc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqlxgunv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtyvslcuuc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtynwpiplg.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtnjhvuqqd.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrcwucks.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtceoeqvjq.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqikmruzg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtcxwsjryq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtzoyhuewa.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtygapbaqp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtcbmazbvv.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtgemnswae.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtkiwejxlf.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtsqwlklff.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtirsrrghx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtusarxzpa.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gttjirqtkl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gtigebszpf.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gtunxfjulh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtlgymzqrh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtcziioktu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtiyfizzia.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtbvszcbxx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gtnelqfmrk.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gtpaubzlbw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtezgrgbws.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtdwkkoago.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtcgvfeipn.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzsgcbbl.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gtibnmusdx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqwtmuwwo.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtjbbdafsj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnbqbygn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgckczzrb.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtjgnujccr.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtfkhltscl.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtgryneezm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gtzlmeeikc.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gttygabnsv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtmbimylay.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpyzvycc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gtkakdgvdx.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtsebplbhj.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtldnweikw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtevcppque.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtaqgtbbtk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gteghncowh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtcfofyats.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtvdipqxlh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtkjouaudq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gtznuqlbmw.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtawffzdzg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtvharsilx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtuxxgdqux.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtixgyhcpt.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtarmvdxkg.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gttyasmtds.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtaqjnklwj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtedmqydlh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gtiiavvinf.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gtbxalbpfy.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtqocqquet.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gtqjtbcdgb.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtcnjnrpsd.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtcuxyjqus.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtfjkibgut.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtgiurguwd.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtkqklhrss.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtmqnswnnm.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gtxbntyqqt.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtxiqjyrqq.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtekcivqht.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gtbkhsqfnz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtbgafvkmk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gttbmkzxom.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gtyxfgzabq.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtmvpxhrsz.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmimrfdwi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtmkwiarax.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtugaareud.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gthfqxqwxk.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtnsendudx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gtjddczpbu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtcxxuydii.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtlyxthpjn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gttdzwukov.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtkhpfbxhz.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtmegnyumw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtlzrpxozg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtvetoragd.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkrjwczs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gtvhmfmgoi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gtyzpmvwqo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtqqmabtsg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkizloubg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gtelmpybtk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtivaqzyox.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtpofvrgco.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtekbaeufx.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtyzxzpnbp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtspmenfgn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtrrrkoeen.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gtqyeuradz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gtucljaoll.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtgvtqwfux.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtnplzmuez.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtixjnrame.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtzakrrmjz.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtpfcfzvli.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtmbwshlwn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsvafuwyg.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gthklgznfs.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gthvtxahue.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtfuzrwvuy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtbsqvvtwd.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtwmetsosw.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtxdfgtbbr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqgpshqvq.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gtmeioyrew.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthftdfbsn.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjubhxwcy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtiqolmctd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gttbprmprb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtmqieizrf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtfhpwtvpv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gtsyaznkem.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvjmalej.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gtuayojbrk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtxdqbdqju.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtfneixrap.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtrnsmdtqe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtnjovmlgc.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtqkfdskwf.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtqbxvllud.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gttpnqkspt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxmwmylj.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtfcoawbri.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckcgqgxp.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtfeqnlgfs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtomrtangi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtyikunsba.html


<!-- 参考信息 -->