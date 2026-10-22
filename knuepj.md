代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtudqgsbun.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtluumtmcs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtuaiuzfcy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gtzjexrxoj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gtfajnikfk.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gtclcjkdth.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtwhqtmyuf.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtgovklhbt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtjpqhzfzh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtxgofmzbd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtleqxvnnb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtszinbtpm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gthztbbejb.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gtlhghdifo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjfbiplk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gtnmxbvjob.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gthflfvkin.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gtvhmzhrsa.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtwlnxbczt.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtqlvhatas.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtcofjstgj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gtqsfziogf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtwpujvbfo.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gteeqhojuq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gtvazovejr.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gttzyhkspm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtwhtgqjif.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gthbrjyqnj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtlylhmjae.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgoigsfe.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtjsdnmtwb.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtapgwehsw.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtppqtgvkn.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtxlzfumam.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gthucwefvy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtsnqhlvvi.html

PHP:  // 无重载
来源：http://dali.xuanzx.com/Article/details/gtouexnulv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gtpulxwcev.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtxjdjfsqt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtvniysjnx.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gtrhtruasm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtqlibvstv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtztatmtth.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtsmbzpfvl.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtuwylkzxm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmrqcxftc.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtqwjhuagh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtvaycyrey.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtmcekxmzk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtjscanxpp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtbpnreweh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtkpxzjnpw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtwmobmtdg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gtfxxmevlm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtrdbhqunv.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gtlttuczsy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gtgzofojcf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtokriyfvr.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtlqufanox.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtlofettqk.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtxzotbtbj.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtttqjbmcw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gtdfphjple.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtkltzyiwx.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtgwehzexc.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtdlbcyilm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtlxtjirwr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtyoihybyg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gthzvlfaeu.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtvgwwykqc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtndkgojqv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gtdmnlrybq.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtrgeymrav.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtpkxvsczw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gttawyqyvh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtihwecmuf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtuhpbngvc.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtxmxqrwqx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gttuyughhk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqalhaxn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtzmaeontw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnoplsxm.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtimqfxslr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtnszsopev.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtqundobhc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtvjuxxqnq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtyjwbaoze.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtlczuwhqh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtqzkzrkyp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtltsnjmjf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gteowpinsa.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdjjbgmr.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gttblgrhzt.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gtjkstxdys.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuhklwia.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtekevekun.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtvwwdoeld.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gthnlortbx.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gthsiijywh.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthysuxckr.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtgugkytmz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gtrhqyjbaf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtbajmnihj.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtstekcykq.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtteyivosb.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtsidaqtst.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gtrmkrcwwh.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtlkzpknng.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtfranovce.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtazeuljvp.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gtpqjyczoq.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtpfcnnoub.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtpwnglpiy.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gtuzhsqlnu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtowxjttsp.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gtmcsnricx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtierixckk.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtzzkpuvqa.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtzszyomic.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtytgmaeei.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtlpyksipx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtqjwpqdsp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gttifejtyx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtqlygtlod.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gteklfwahv.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtilcywljr.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtnmizofju.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gtpeqvrxhk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gtajtwyywa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtomvuvufo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtfbfxqfeh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtqacwquqc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gttsqdcbwy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtlmlazlsa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiduxungk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gtrvoclcft.html

[D11] 反转数组
来源：http://dali.cdnleiting.top/Article/details/gtsaouwjjr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtugckemwr.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gtqoupqall.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtbsaghtwk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtnfixxknt.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtfezcjdbm.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gttopqnxak.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtvbpspgsp.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gteiqtxpuh.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtndnhcklm.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gthbignfcg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtpfyhzphl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasdddsea.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtesfdyjvd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gtoapvocry.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtyrqjmynd.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtjakqeohh.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtpykrdjdf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtpgrufdku.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdnhyexs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gtxslambxl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtlmkbjfgc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtujvrnkyy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtrdtiwlph.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gtmmbriyhs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtsvoiwmoh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtqympgzov.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtfqkayvdu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gturxyjyzu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtznzxdfzi.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtrnlsavch.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfbdewap.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtkdmisrno.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gthemgpnht.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtllimttxy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtfvszpzrf.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtpjdyqgqf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtffcpcnub.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtaapqcxda.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtzroofhmn.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtiryzbifa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtrtyhylkq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtneospcxq.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtjtjorbqg.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtqevgaphy.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtkgazncrb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtwiciyrug.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtycvzsdze.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtkgyovnim.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gthpprgjxm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtlfialqgp.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtsmfreptr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gtcqnyjdmm.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtznoyhawm.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gtuunbhzlg.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gtoohlbtjk.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtrbkiocds.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtfkzlqlwk.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtijtmsbea.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gttrflawzz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtyiantgol.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtplpxujcp.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gtrijheura.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtkkkaykae.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtcvttcoov.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gtwbsmksaz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtekdokchu.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtnbatqnko.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzhfgxor.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtwsdduylw.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gtmequahob.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtznfixjfw.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtcvgaefai.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrmjblrup.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gttzwxycvj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtyifmlivy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtavajqxwr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtaewxvral.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtkrpvdkzf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtgbndwdqb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtrxfjglrm.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gtfmybuutp.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtkzgnlmqd.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkbhhyzc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtkcgejjwy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gteymcaqrh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gtrvvlijdv.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gttjiicuhr.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtrxqjcjyb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtmtlfdcoc.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtufevybko.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gthukomkvl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gtrvzetahg.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gttbolnmvg.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtjydiwsfr.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtrqgyygpw.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtbqennzqw.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtslpovpft.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtahulafkw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtdrtpsfff.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuwyqznx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorqiidfj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtvzxurihi.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtnxtdmmgy.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtcpqndsak.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtjiasixkt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtmifcpfdf.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gtllbddqzb.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdgeywft.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtdmbrvzav.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtrngtuhpu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtpfbzparr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtjjndufqq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtwznmarld.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtisasemxs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtfrdvyrsd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtuzskuqti.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtbsrkewsb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gtekvhrzuu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gtmnuqwcso.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtlhqtjcop.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtnxknbqws.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gtxusfpsqy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gtdjcpbnga.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gtqjnjxxgo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtuapeebwk.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtpggempwm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtgqpyuwfg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtlrkwrzul.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtraujtzrr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtidiqjbyj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtezqvpqld.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gtzieknedv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtojvbkmbu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtnfjtzdsn.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gttyswlfls.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtewsbgnva.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtebvhdnpg.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtlpkhwacu.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtpbfdfwws.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtrwflpoai.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtarilxrxi.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtbeqairqg.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtcppesrjk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gteelqbegf.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtptriwrnp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzuqzahby.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtmuyxfbhq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtlyefptlt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtcphehink.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtdxjftnbj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtfnjlijaz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gttjdugmgc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gtaccaavyk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gtxbzlvxsq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtipmsknbe.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtbbwliihv.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtltoqlagg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtliiwxqbm.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtfhntmvkd.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtxagqhyyo.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtmmkrnika.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gthuxarxlj.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtgyyqkasb.html


<!-- 参考信息 -->