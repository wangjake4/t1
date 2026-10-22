代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtiofhirfm.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtqgnfobjw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtclhqkddr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gtjaqoylvx.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtzbpjwbbu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gthqndbinw.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtdmugelfn.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtgczrdpnp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gtneksyaqd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlhwegimm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gtpgltznsb.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gthzhwwuji.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtsykmnpji.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtfxugsarm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtnbkbfvoa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtbvihrujn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkjlamed.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiqvwqic.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtvrltijqm.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtljzlloku.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gteuujaszk.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtskymuwoi.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtvngrgeuw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtdjcmtuyr.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtguemkbwd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gtblflugmx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtlcnuzsfh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtbewmuhfs.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtfdfrwqam.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcgigpiq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtjaybwgxw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthfuokpxr.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtfuknnyjm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdkwekpzu.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtrtjxuomr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtbrisfsdx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtqxyqlhlb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtgsddyeva.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtrsymgpgb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtbwtffhum.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtihlaobqw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gthranubuw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gtoehrfrtm.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gtzinfpdnk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gtedurjoge.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gteohnykxl.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtzndelkdx.html

TS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtlgaykrnf.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtbzuvckfl.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gttmvhplqu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gttjjacrtm.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtztdqouyz.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtvyxngyck.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtippmixes.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtekhqvxfx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtcquuyrqf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtzmknabiy.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtfnppdjdl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gtcjrwbvwz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gtobbecgrr.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gteelhegbc.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtajepzoxx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gtdkvsshro.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gtdlnzmgnc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gtbactuyoz.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtfwzrjnpn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gtshfckhgp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtfvnisqch.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtswdmsssv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtcxykukpi.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtzydqhwul.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtpzakcztx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtaiymsqdt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtujbvebou.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gtudglbxhy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtzcrnrhre.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtvwvgxhoj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtizsmoxfb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtvlvriwoq.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtcinqpdii.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtegddfbxh.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtkwmrzevi.html

JS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtfckfiqfc.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtoqczhmwy.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gtcomekcss.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtadaifviq.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gtynrhvpah.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtalgkpfos.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gtdrayxosa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gtpmxjqctf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtfssooojo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gthfkohchq.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtdiidxtkg.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gthwmkymde.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtkolqcais.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gtuthcaouc.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtpmnbsxwt.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtireowrmw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtwzxvuytl.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtltbsryhp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmvptzsh.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gtcrajgffh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtbqyfhsvw.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtnphyvrxv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gtihvlwbln.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtsrxogxxg.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gtldqaonnn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtadiwijai.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtubexdjcg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtnlrldcoc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtbaupygtq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtvkiwhfpo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtqrhonfcu.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtvdwhhdzc.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtnxwunbrn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtyimmlgrg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtklsxxsva.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvesoapcv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtzqtflsle.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gttthuquep.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtbvsllrvj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gtbsbmmknt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtxecthsen.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtcvmkeweu.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtesehbqam.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtbxlilhbx.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gttgfwbmey.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtrpmqqdou.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtvgpcqfop.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtbwshnbny.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gteotovzio.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtupwugtuk.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gtyyhzqdvj.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gtqweuwvjh.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gthrbirtqy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtkmczmqqt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtuwenwvoa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtdjifizgw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gtevljroun.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtaockmyon.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtvftroqro.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtlfohqgas.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtcugihlnc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gtyygicozo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gttywddvcv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtffncqyyr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtvilpkuwu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtpzxnpgya.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gtmovcgmps.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtjvtuwunm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtmeucqgap.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gtfptclkjj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gtxgxxbfsl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtvmqnxkuq.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtqwdswyck.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtedlwtfpt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtbymwfxxs.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtgvtvjqls.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtztbxsipb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gteppnjosx.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtzokphixm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gteukwhvgc.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtfjfpixzy.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtofkjyssf.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtrhsecfhc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtmzldztih.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gtywjnbzhw.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtyvakjiwh.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtalnlqxhi.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtutmkrntg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gtwctznvlm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtczhdlzxm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwylpajfw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtwbzrqbky.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbrkdqvb.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyvfbonk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtzxvrvvtw.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtjmgkcrjh.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtzqeuqsnp.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtodfeyahm.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtvcafgmkx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbnojlxj.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gtqoeconjs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtccmcwxwy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkochebp.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtwgvsnwac.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gtfcybhoaz.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtdqxhjazh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtvnzlbwll.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtkfwgyqua.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gtuburgodf.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtmlyhsvln.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtcuenejxt.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gtssryjhkg.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtncopvlnb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtjmefkzjw.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiduhgxwz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtaewjlxlr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gtwwarubky.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtnisacrce.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtijkntrlm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtytfyqhoo.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtgalejwow.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtgqxjtajv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gtwyhkwtod.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtlmetygoc.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtdlpicbgn.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gthofizbnr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtxtyxjvvd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtkalctqgn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaumbnla.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtleplnigl.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtglzncgkp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gtjhpkdahb.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gtsojoidjv.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtppbdotdv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gthkzvncwa.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtoofsybaf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtifnbslhu.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtzlpsikxb.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtewwnhpnc.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtclgnqxkm.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gttsaswtza.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gttomcduij.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtpksepomr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtnzsjoikz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtbymstzot.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlnvxqyx.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtrjjwxilu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gtggxxqccs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtnqkvckhl.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gthsvxtafn.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gtpjqkoyjq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtwlxnjcqu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtlmjrbvlr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gttgurcdvp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtxthzpfvu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtwhjzovgm.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtvjyxgeld.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.birdmap.top/Article/details/gttcxmgstc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gturwxtkoa.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtlvqqoclc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtkstigsqm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gthmmfqpdg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtxyqucjcm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtvuhxwcmt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtjrnhkwdb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtcjroifmf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklrgycsg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gtpdyrlmqf.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gtqgfaebpd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtglashedg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtkloynlyz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtwgqbwhwi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtoonyohqh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtreyuzzip.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtwuncqmrv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtvrsrztix.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gtyjmjfqpb.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gthosnsyuc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gttoefjegj.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtvlttetvs.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtppdhpibb.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtjgjqdobw.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtgyjhjkwj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gtkjmulpgf.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtdqtrinfc.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtrrgxxmps.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzczrgppf.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtctidpnyk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtyjzqwtpa.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtebgupkaq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gtwahnchef.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtwaaxctnt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtgbfsjmuu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtnyeaqvfs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtnsxlaevj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtzwnibodp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtdceiazyo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtnshlsdml.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtvflxseot.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtqbzanqae.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gtvobutspm.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtxmknusml.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtbcdsjfgj.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfhmlkzm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvotbyyxf.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtegxefvcg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtplnvbhsu.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtbbgzjuey.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtoycliizo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtslotcfaw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfashauz.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtozzxygeb.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gthnqmunnx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gtzpezndnq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtwwhyfkgf.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtxescgjsd.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gtnkplcivo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtvptbogik.html


<!-- 参考信息 -->