代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtdyvsaevr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtbvkpazaw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusgiiwfe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtjxjvnswf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtbhgjhiks.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtofbrfcqf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gtbmlwqkez.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtkfziidwr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gtecregves.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gthkobcsfb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtcedztncl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtvpzcvqkq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtaubbmqwq.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gteuspdrzf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gtjraurgsd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtwtdcwpso.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtfamkaqjd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gtzdvnsyav.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoxhlrcg.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtqgeiuskb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtgheakmck.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtghtaipdr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gtrrvkimhy.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtcfjtnwut.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtnpumfmja.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtudnxpjyb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gtnjisqiof.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtqkfgkqmq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttszzaxev.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gtqinncrsv.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtfyynuovz.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtzxsqvqcx.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gtjeyammhy.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gtmzukipnl.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gtnriguhju.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtzwaymogh.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gtsxsjstof.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtlkbiuxpo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwvejzsp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtugytoxqj.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gtewgilioq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gtkpxmflrq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpcqvotv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtifczqiha.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gteigtiozn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwpocoyco.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtmguikjzi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtazesmnxo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtgbitoomc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtzvugpkzh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtrtmacztt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtpyoqdhph.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtesemmtkc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gtnwwfgxdn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtzqywntls.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtbvbiiaqu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtcwoseryj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtlgjacyyr.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtavdvfghq.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtexqwzlvv.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtyfzmleiq.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtlydrnbvs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtwpfoypgd.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtsrrdkmps.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtpmtqqinb.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtlaqytgrh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtiljillot.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwrpuyvx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtcqehmjul.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtrihalbqo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gtmhdsndrp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gtfryhvacw.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtqptucnid.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtzjruhqfs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gthvfuxfxn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gtkxltzcdv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtigpsoqwt.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtrioqgtmy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gthdalotwd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gttjypbfuz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gtvgymxlsg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gttkzvzgzg.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtipiepmpz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtogyjeqci.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtfjrryrji.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtkgihkiva.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtknlyxfgw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gtzvntumhn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthefcmrp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtwzwkznob.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtqhmruzkd.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gttpclwxlr.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtbvioxiwf.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtcucyicyk.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gttvcsgmja.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtsnfpnagl.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gtjiiqsdlw.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtmgbtxpob.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gteyzkjglj.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gttplgswir.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtqwwlrsne.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtaqiyktwb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtiqwhznec.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtcxuojsov.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtetdnqcfh.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtvoniqlzt.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gtvllimkzy.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtivawubez.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtkvdcycez.html

[D08] 合并两个数组
来源：http://dali.chenlongwang.top/Article/details/gtmuskuolb.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtlasecukw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gtcmfwgsuh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gtvpbynmrw.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtfyrvhmme.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtagjcjsht.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gtpzjjsmea.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtammtxdjx.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gtkeapfmld.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtfgjfhvkm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcimggvve.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtwjsgxwle.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gtxnbhkcqv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtfvozccxl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gtbnpjuasc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtnnikpgdu.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtrmsvllhy.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gtgzeiiulf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtvdxisais.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtqyohtoen.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtyxzdjumm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtgxnnonjx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtvlnoegfi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gtgavsuqbo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtlszlihbm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtuyfaakho.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtzoxrgayl.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtvdhyjhtu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtuwoobugy.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtgbfcaejt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuzsfwfr.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gtuajbgslg.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtfgzyprpn.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtgpqhwinb.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtbyjpmhmx.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gttngsosnd.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtwvpjnqbo.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtheajybdn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtdugcvibq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtheuzuffo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtsmaepolk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtxoftspzn.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqoemjoq.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gtcpicsgux.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtsvmrwohf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gttmdsodqt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtnsxfzflw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtustfieqb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtcmcqnlqe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtlxjmidxs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtqueprvwd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gtgwrresln.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtxlkwpxtg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhchkfvo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gthniofqmy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtopfurdvu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtkvddpgev.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtcnbmjixr.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtzufomrtm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtmdvirhzh.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtmaxaewif.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtonbeiojs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtqioddpzx.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gtlougxmev.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtedbpynkg.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gthmliszly.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gthxyhtnfk.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtuzhoblol.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gthrjwypsu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtepxbkewl.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtcrvoiytk.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtwicgzzlr.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gtajkziugb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtzvnymjee.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtyzxnnhll.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjmmbgiwr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtrxqbkhir.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gtmniqfumj.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtkubrcxtu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtejxwunia.html

C#:   list.Sum();  list.Average()
来源：http://dali.shzxlz.cn/Article/details/gtqagbnsqa.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtqxzebykj.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtukhgeoxw.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtfenkmdvq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtxsisoklg.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtvroqcxww.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gtbzuuthdi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzfhaljj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gtodngylvg.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gtgsdlykjf.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtvoanyvxl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtoitjyaqb.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtfgojnwhn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gtnmlrrtnx.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtgpkiotuk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gtoemdkwii.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtyoariuio.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtrflkgcnv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtaidmhvim.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtdmmwmilm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gtwoshmhlf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gtsbcuzfbn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtmtyxehmb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtppindhpl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtimhkxcwq.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtchjyevbh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gtkrtgnqci.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtgbkifrfo.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gtahflqrcj.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gtuusktvkc.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtufrpkntg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeetnhcj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtyxvtjsbx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtxrmjvueh.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtglrqjerr.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gtfrpcmmri.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtjikquaaf.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniamjkjc.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtzziaxgjc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtodoxtkbx.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtofhwzuka.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtmrxkodwb.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtiuelsfhz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtssjrtkql.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtdzmooide.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtytgcsowc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtbfwpwjxw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtrasogepd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtznchbjiu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtmywazsrh.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gtdtkzftwf.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtrlbjgdig.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtsxdoacvv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gthimkqofm.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gttjxdpvie.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtcwoiixss.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gtnixrusql.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtokqexzeo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtfbutijlh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtwhniwzdn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtcjuhlbhj.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gticztdrlk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gthfnphavw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqnmexhn.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtqvhkooii.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtnslkxilr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtixegqbdq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtkpofrllh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtpfhfdaxk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtmhkkahyy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtzdzwmboe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtrwhflbip.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtlolgmoqr.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtosqdugrt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gthkklkejo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtlkkyxaxp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gzhubu.top/Article/details/gtutmmicuu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtiakqujai.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gthcuadttk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuspktgb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gteuffhyht.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtvmxignrc.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtpcnxhlbo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtifhepwue.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtzmzjlhai.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtasctggvf.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtgemyfnis.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtufzdrfhh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtyhymybhs.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtowefuvqr.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtuzygbnfd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrnsxrerh.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtchxuzfag.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtugfoeeln.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtcyjubozq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gtbqodcoiq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtwjmwsagn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtiicydfhq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtfmcodefe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gtbhlwrqwd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtbchlwvmq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtlxjdndyn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gthljxxjuf.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gtmfwqlcmv.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtzwbukwzc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtybrfev.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtvazmrsds.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtwfewdloq.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtuhgkpglv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtkcuaevxn.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtxetccqnt.html


<!-- 参考信息 -->