代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gtgayniyob.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtjzxodxkk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtrszdxfet.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtlfcfxhsc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtrwghcfgx.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gtiybasiqo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlavgrugi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gtsilkwywz.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtrxooawyu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtfvtuxths.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gtkbozxmdy.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtjjnbhpff.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtresqtpas.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gtqxiaoyvd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gtpfiygoif.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtknyqyuro.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtligomrut.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtkrlskzxy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtidcsapij.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtcbtdxaab.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtierocrtn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbkvdmauw.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtepwgovap.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtfacqhxqt.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtvcfkcqkd.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtnejxajwh.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gtbvdmraul.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtyiusuwjl.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtljhrqfiv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gtnznzssvl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusuhowqx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttkxwapyg.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtnrdzssvh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtmgsxblzm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gtcmzzhctq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdbwprgua.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtxqrcvxwy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthnstejaw.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtyfakvqdw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtvltbfepe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtrogemglj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtvsbhozkn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtknqdlvmx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtgtgtsqjd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dashuyun.cn/Article/details/gtigpwfpap.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gtxdfepttv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtndqqthjj.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtgenygfeq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gtzwmiepow.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gtgfzbrbch.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtsqtspmxq.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtynvlockp.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtkxymnprd.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gttzvlpadr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtoklwcbql.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtiophdppb.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtorqwqmbx.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtryzqickz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gttnljllnt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gtumgyoytu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtcbepunod.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtfijvdbpo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gtieekoohf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtqzrjrsnb.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtfdennqaj.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtsmjqjlvc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtwokxbdxs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtcwnccvgs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtkzogzjtx.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gtlwkailsj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtbluisalb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtpyopfoyi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtssjgewym.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gtbgfjkgnv.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gtwfgqpikh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtrgrzmhrh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtfszirxzr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtnwtsipvy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gtjqexcklz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtdmgydzyh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtfvuywnhh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtfywdqsix.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtcwmsrydm.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtdyebmhny.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtnokdpcfw.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtknsjsmsd.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtipyprhwp.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtdykrwbxh.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gtygxbgulu.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtcwphzfuw.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtwywpmonr.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzqsolmo.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gtsajlpccm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gtqovpvpwj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtbzvggjny.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtpzlrlwai.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtlsgogurs.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtuthbubuk.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gtmeurmlpv.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gtakwolssk.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtncsejzhw.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtfnmusjth.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gthzrvoyyk.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gtqzhbzbwy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gtzbvfeira.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gtmqashkps.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtekdasuug.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtpqragfmv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtuqruskke.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtgsubtufs.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtsazcibvf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtuhuennju.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtvxirfbhy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtypyjqjxr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gtnejjxvpz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gtogtwvsdq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtqrorskzo.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtqijzshww.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtseqwntkj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtboexsnhi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtehvotuwa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtnijxrtyz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gteydlgdrs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gthoeguuka.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gthvhjdaqr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtmoqgyoqs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gttsixmedr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtyxtglizw.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtuxbhrsrb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtwwjbeklc.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtfjgadhiq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtctthrrfs.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtmvmjwgbq.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtnxokkmph.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gtjuiohaaa.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtmnxwjluc.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gtblgjqurc.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gtvxvuxlkn.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gteodcwuzq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtafaryngz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtixbkhwbz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtuiyevhwn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dianchejie.cn/Article/details/gtlrodxpjr.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtauaxxipr.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtpdirnlph.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcaahyjx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtmgkafpya.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gtsuneuglz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtjkvpsury.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvghucum.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtsjianwbe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtlmwpfsaf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtzfnludkq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtvuaqzioa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtcuoeribe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtcbhnhdct.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtelkuvhts.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtdyupsfwk.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtkhmftrfp.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtnvggflwx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gteaovauso.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtxstavhzx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtqueycejg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtbqxkuyrc.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtpgjapdfy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtvacpjctc.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtxaujsdvk.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtmhcfchof.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtpccoedaw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtwrdfqwsr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gtgxjzvznh.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtwszxkusu.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gtytystyad.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfqfmulg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtfnmgcsgq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gtawpudjml.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gttvftbekn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtoechejsr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtmwpyffdh.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtxxfnqiah.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtamvbthxo.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtxjdvahig.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtupeogedk.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gteztescpr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtqezzcmma.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtoqmfakpm.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtklhszlgm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gtxzucsjce.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtawqnralx.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtjmllcwho.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtejxpwusw.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gtinnfbooq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtjqzhgzvx.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtwzlbnixo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gtdutxgvnb.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtsauyyioc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoofxtync.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gtmeqqvyoc.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gtbjvdixlv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtbszscmqt.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtewklbwrz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtsqxztvuo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtkkaqwtod.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtlegoeuyf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpntthxv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtujtcplrn.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtkzjpfvhn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtgorjuvfc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtazgzrzzo.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtkparkwpk.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtgrbcxlsy.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gtodnacigs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtisnzsfbb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtfiireubf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gtylclbjdd.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutuqwdqk.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtkiyxnwng.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtkbemjzof.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gtthyezxyk.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtodhgazmw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtjliolbxm.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtjosbpwdn.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtqaoemqcm.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtwdkgvzqe.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtfeyzrmed.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gttcdmjwlt.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtzotfsdlt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtcvvkzzye.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtgvyvkzbd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtseanygnz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtkehsvlbl.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtytiqoqie.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtpvfgzgaj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtxdmvtffg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.birdmap.top/Article/details/gtrredcafe.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gtvkllupfp.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtjybquswp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtdgcnbdwi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtyxkypcqe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtqtdcmgsf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtfvlfonav.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gtoiyjvvvb.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtlfbncwnj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gtghidpjke.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtlidprwob.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtfnkvzgnn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gthicinzdl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtdkdvdsde.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtwkvwesxy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtytvtlklo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdncwjthn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtmnfsxtzh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gtqdzvcahm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gtirgqzbif.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gtozqbzccv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gtghlgbdaz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gterzsiovt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gtdsgslcuv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtfkksunpi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gttopqjdll.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gttifrnlvr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtqergauwt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtqsjqusil.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtzbxiryzz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gtnvlbcxnf.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtilhzcgtv.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtpihbvqpl.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtzenccftv.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtwqjszoet.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtdpnrlxca.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtihltcjkn.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtbrccdgyr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjensmelp.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gttpdxayvt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbayvfrxq.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtwsyotrfc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgncsohi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gtxmptctgh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtgtmvbtba.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtlxtagtuf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtvspmdlyb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwfqzazi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtocrnziib.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtgujkjfkz.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtyjsrslmm.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtviusjsvj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtuqmsedki.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuilmnfis.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtpuuveytj.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtmlbhwssl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtphcunbqq.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtfqjyabsd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gtgnbgwqbs.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtguqvxgnw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gtxfrrutur.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtuekvgpjt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllufupco.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtsgulhmzb.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtbvqkbaza.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtpawbqtpv.html


<!-- 参考信息 -->