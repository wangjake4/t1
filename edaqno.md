代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gttmtrsoxx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtekdxbrrl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gtivetleou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtfvthkcah.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gteilyfilm.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtpuwrqxjp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gtwkriysxt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtnoyjbsiw.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gtcpsfcrnp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtdpzjgqqi.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtxibjaspq.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebvkhyba.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtkcrjnlor.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtkonnfqon.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gtdogawebx.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtzierjdtq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtczzzhjav.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gthzuxvsnn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtgvnarbcc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gtbbqdclwv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjcrstjp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtzgxapkey.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtwolzvvyd.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gtwoqaviks.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtacxsgffy.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtznrhikph.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtfnblcpda.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtrlqoprvi.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gtdtosgevi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtgktwcasg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtvuplrxgb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtogluicdr.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gtolpfeaej.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gtncmmyszd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gtfsipkozi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmddbcppu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gtplkxrdsd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgmbjoccj.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtcwnolylv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gttbjrxbtp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gtrepwgszy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtrqyesexk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtjczibkhs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gtpagqrbkw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gtdtlfzelj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtasuzhrzm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gtffshkqie.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtcavnqxdr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtwqlffzzm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtazqntcay.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtpgwycnpw.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprpzwblx.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gttufpasyh.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtdefszjmy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtobdtrnqj.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gttuitwodi.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gthxkcxwwq.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gttfkyaegy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuftytywd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gtgsycqttd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daxiang520.top/Article/details/gtmwmvuyqc.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtsuxhjdta.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtbjpdvmtk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtedccbjyd.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtylnyadht.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtledrtsjx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtqkklcrdu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtajagcccd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gtocgncsyb.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gtkilusbng.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gthvohfelf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtjworwcfx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtqtycctuy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtntvauwvl.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gtolailltw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmwmyjwk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtnavzzbzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtftsymnpb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtltjxhcjb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtlpfiyetl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyzagvgv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtkufwijnu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtbkwvqtfz.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtjlgmqdyp.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtbdxgzalu.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiisfmrg.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtytmzutsw.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtjrvswbml.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrildfxq.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtzvmpdsil.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gtfcmswkpc.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbmnvgpu.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtqbcaadkj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gtvkwwgpni.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtlkooytna.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtcyjvbooe.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtfszielag.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtsobfaasf.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gtgpjijvwt.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtfoeaywrc.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtsakbgibf.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtifovszmg.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gtsdcvdlge.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gtqbtcpcte.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gaohongyu789.top/Article/details/gtvhwexmfk.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtgupemadg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtkeyqcvjw.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtkknqxnvv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gttnwzxybw.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtlakrbajy.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtibbjbqsd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtmjhiokpv.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtkfddfwye.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gtcppmadru.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtgbagvuby.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtrorsqmly.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtmunqlsni.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtwjmbbuoa.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtjkhglfnb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtjdrczfgq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtwqzmkakb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gttmvoaxhe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtbjimhbru.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtjqnmvtkm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtpzbfboor.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtgxdtaihe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtrfnuffte.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gtntljteki.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtnaapjcxe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gttpzkkczc.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtmyhtmvup.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gtcskviazt.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtficpnton.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtcflrmkqj.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtcanbyiyc.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gtecqtmtak.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtlrfoowit.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtdseqvgba.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtxfmdesjb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtkbvbaevk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtwfbcrtgb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtszktttkx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gtogzcbvxb.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtubygvlwu.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtyswouuza.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtzqiatnen.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtagclqylh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteekdsfbq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtfojmiykl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gthvngihcx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtjplohpqx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtodbumrpa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtvgnszxze.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtwbrelvyd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtrqmjanzi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtfxmqeleu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtnxtezslk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gtesvtskyo.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtalvhsfku.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtiujfrcak.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtusvdjzds.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtgtjbjqrw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtioercdim.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gthohwkrre.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtgkjzlu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtgpsawjkg.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtenmoxgqv.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtvnjuijnh.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtiywsdnzl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtzbfypntc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtinfbmrah.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtuvkyttwm.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtrqwhzbvo.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtyinyccdr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtgjdqyjnj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtikmwcyak.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuaylwtw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtfcldwgdh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gtuhzcgwsv.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtjttonuht.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtkaifddiq.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtevtkzczc.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtpvdvhdev.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtuvwfyofc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtcyjotatb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gtidhktcpb.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gtfmsbpxft.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtlikcwfpd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtorgxqmek.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gttffqgnrm.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtqqiyhzrh.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtlpodqbum.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gtyemojzcq.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtcirbqjmx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtetddeqby.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtsfuryruv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gttmrzljch.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtislaycjk.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gthnkzbabt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtfzzfzvyo.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gtkuytzgej.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtypqmwmir.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gtuxetdegg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gteqnarvze.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehunndlh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtnplustew.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtsmhzsvvh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtufjjecur.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtiolkqxkx.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gtwxpagafd.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtxjwfdfdp.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtnaturvem.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtsrvgfiyw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtpidrmpyk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtceibjvig.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtkicojotf.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gtnxydcmgy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtnqcmtdhg.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtuwiiaccr.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gthbkwlizb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtsvmlucij.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtcfadaonm.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtnpjqkspd.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtkpjncaxh.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gthygyotyv.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtnbaxogfo.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtpdfjprlz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gttsvathez.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gtxyfmkmud.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gtjvfrojom.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalhzwewp.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gtfgpaebgd.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gthhqrustp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtfvpwmbky.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gtxdtsfuqg.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtrwjwefho.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtcyltpchr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtynolielb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtscjhbbqz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtamlhuyqr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtgjrnzabj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtfihfqikk.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtruohthod.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gttytlbxdu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gtlcmjqfii.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtslscapol.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtbfcyvdyz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtnkeypshz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gttafgjdec.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtyveepftq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtgjgbfyuh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtrmeytubv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtahyinibj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtjqcikdov.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gtjeegrueo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtoaftaikh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yongpay.top/Article/details/gtuakuwwiq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtvfkppvyo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtxcvwbyqo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqlijihm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtxhriovny.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkawtdqgi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fengsongda.top/Article/details/gtrergpiyg.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtyrefmlag.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtyglirtmr.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gtjvzpfvrr.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtdbsdkbry.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtjqqqgsxz.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtedagkbiz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gttrcfqeme.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtkwieugan.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtzqxgizid.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmltbzhto.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtrnisxlgy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcdnqnboh.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtuoiirqju.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtboeyfywm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtbbpkyded.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtzkfahugk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtbgrqddyx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtvmczljdt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gtlddnumof.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtbqcjyoue.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtazeudrlf.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtxndjyhlu.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtnnqroprz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtayijdauy.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtljjszjas.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtkdnhehmb.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtldxgktpd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtztgqkdri.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtbmteclno.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtdoxozumt.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtnbjvnqrp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtdoiemxgj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtqjoebczu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtvheryjxw.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtpdyendae.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsibtndr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtqpjyyfcy.html


<!-- 参考信息 -->