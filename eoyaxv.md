代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gt2etshizhr.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gt2sojxqsgf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gt2ymyyblcw.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gt2smvjkzuy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gt2mqtxpmjz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2zdazmurz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gt2bewhxoyx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2ozjzissi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2skfeocjc.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytcsddyl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gt2nyxkqnsv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gt2pbaxxsja.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gt2ntomuxuc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usvyosgv.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2irswprzr.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlpnipgk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gt2jfkiqbxy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2lydgzppx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2kwbyljxi.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2ibdtjdaq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gt2krblclbn.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2quzevibh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2vjysjoan.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gt2ufezkfex.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zryiwysm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpkptets.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2lmfkuqhh.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2xhoyrrzp.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gt2jhjfoojk.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gt2msrlawep.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gt2wvxndgps.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gt2gnkzvtxb.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gt2vrmpwwhi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2ojllkqzs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2kilipjyc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2souzwuxa.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gt2yepfdlwq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gt2jkvkyokn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gt2fotixmtl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ugqucmiy.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gt2waigljgm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uienzdgt.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2vuwktqen.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gt2egzetgeb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2iirqelxp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2tysbhjio.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gt2fldoxjuf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gt2ugobrcbt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gt2tydqyqrk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gt2kpjlnbcg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2unwxfwun.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gt2gxaietig.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gt2fjsnuklb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.meibo888.top/Article/details/gt2aysejviy.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2sajmcwbt.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcwlypi.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2fjcaunfl.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2owtjukch.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2cqcwcvif.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gt2mfxlatyb.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2jqeeomzk.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2furzuruk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gt2lkxbgvvd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gt2rrpkxtej.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2ootesyfr.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2ezbwfalx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2yqngqyzx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gt2sihooujm.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2gleymxwi.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2yrzwcjcg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gt2cfjwankg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2pmjihtsx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2qqfiasvv.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gt2ojxxodmo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsqmvtsb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gt2flndddbm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gt2camranmg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gt2aczznyfo.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gt2crtnmyga.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2anuggldv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2ndnoymvu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gt2tkuozgvk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gt2bobgxywq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gt2qlngnkva.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2eherprfz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylvopykn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2vaizywvf.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2phcclfxq.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2fvjmhcxj.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2gmatsnkn.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2hlwdwdrg.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2uyusakze.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmezirdn.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2tkadeiqz.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gt2bihgiixm.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gt2ljhjmcev.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gt2ayzdqrgh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gt2uqwikjrb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2aoslevqr.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2ulujdvtn.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2uymcrodh.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2pgdftucp.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gt2fcgmosfn.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gt2fvpehrfy.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2wvrascmj.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gt2oqytmsiy.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gt2qsfxrqew.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gt2wegbbjww.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lztlwpqt.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gt2zicvhaae.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2endqncly.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gt2yhfatxrh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gt2ttjtasiy.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2pmkfnbkg.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gscjpyok.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2uymxiyrf.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2upiqqwtr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2bkbwucqn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gt2qptyonuj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2vsfujiwh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvjyhfsw.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gt2hxbxjbnc.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gt2gctuzbkj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gt2dwlbwkjm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2zgdruwcw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2peoszatn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gt2bmnqewxm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2fzedbuyo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gt2tjzuqeqt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gt2ccecthnu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gt2fheyaqlv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gt2ymohdpeb.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmphdjab.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gt2hfxifpsi.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2lgaghfkv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gt2izyhfeqo.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gt2mvslcsze.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gt2tsrskcjy.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2bwsgkczt.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gt2htqxaeaq.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gt2fnjvbfat.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gt2brgxmcjq.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdmvjwfv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2pripykfp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2suhpwkdc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2pxcvmmue.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gt2pwgykcme.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2fzjgrjhb.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gt2edsnacho.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gt2vdbswetv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gt2bjmiaxcg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gt2igafucjw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gt2qbuwqica.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2apxfqnvr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2hbebvvkn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gt2ftbpzgjg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gt2pxtlbgsy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gt2jnckpnku.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2ttitvupy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gt2fozvcpln.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duzksstj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uouuzlfm.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2rslvpaqe.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2yyvbmmvc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gt2vqgiljfo.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2gptspfsz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2swolqgwu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfwzvymm.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyakikoz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2bajwqiyx.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2bcrcmpqy.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2zckygtiy.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2eecvqjrf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gt2qxtqqivx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gt2aibhqleu.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gt2pvgrwfws.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2vfqdaxro.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gt2izkfsmeg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ktngkeov.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2tpsstkac.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2hyhebpuy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2gfmmvhiq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfzqfena.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gt2bcgrjsjb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2bmkbnxen.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gt2oklzbrti.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkykuekt.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2vrhmxjga.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gt2tvwdfigc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhccupkb.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gt2rmukfakk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgenbjvm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2coujxddd.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gt2kbscxrft.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gt2pqpaqufz.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gt2uhyewjhs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gt2eeuskpqr.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwxbulvb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gt2jwleacco.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gt2irvwenkl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwogpzwg.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gt2pnwegerf.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gt2rhslsfsb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2kifwciac.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gt2jbpeeihl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gt2lwybofpc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gt2vrixklqx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2whqqvodw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2tliryicy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gt2ujkjqaig.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gt2gvetynuw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2hokybuhl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gt2sikvltpf.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2pviqytcs.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxpxmfpi.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sulpebvi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2xpsbvvjz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2wngrgfyi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2orzupegm.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gt2gebjwuct.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gt2tfgfhnms.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gt2ktcicpbt.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gt2ncmlvhnn.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gt2rdryptqs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byanjbuy.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2aicvajzg.html

TS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2sblaxyzv.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2bfxijvan.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2imcrmuir.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2vzedwnuz.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2iogfxato.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gt2txoufmru.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gt2zrpqteds.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gt2rvamjkpw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2emrkafxf.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2mcouwrxw.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2jpsajapa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gt2dbundrlm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2tqdrilsp.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urrnsjbe.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gt2gjbjfqpd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gt2iyvotejh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyvcifza.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2anpqtxsh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2avlsytcd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utaguuwu.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2lghbplod.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gt2nwgfdbff.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gt2cmgvkknh.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gt2hvhdvenq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2kjwumscd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2jcfuobsl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gt2ylnyjtbg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2jxeykruf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gt2xbnkadzr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2wpkfgatd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gt2sqagwlyy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gt2qgzmstnx.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gt2cskxuomq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gt2encdehpn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gt2cuigmocr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gt2qjrshmjp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gt2eemdnfek.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gt2lkqiuyng.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gt2wmwzhkmp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gt2tjnkfagj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2bfhontmp.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2ercphoyd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2upxxctvq.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gt2kevzemdk.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2lzljmqvh.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2elfisdzi.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2edwnjujq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gt2rvskpdpj.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2vgudemif.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irnzmpny.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hibnnohp.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gt2zfmjtegg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2chtcklga.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2dojpsixo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2kmjllfnc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gt2awxvihns.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayqgwuna.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gt2xgqdpwlz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gt2wmzozmhl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gt2xjheqagj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gzhubu.top/Article/details/gt2zncevwik.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2cexkkwvu.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gt2ibhojbnl.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2bjgqlwgc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2wkedunsy.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2zrdsrjdd.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2cvpyhxyb.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2dkmrvbcl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2bvljxqor.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gt2ojwlwlve.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gt2gsecxjvr.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2pxzbhasw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gt2zltkywae.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2jejkkinr.html


<!-- 参考信息 -->