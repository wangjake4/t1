代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtomgyxhei.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gtlushbiwn.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtvdqcvjsz.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnkdqidi.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gtvpyeeetx.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gtaosqxvzp.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gtdxwkdpfl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gtnetyioao.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtsefbtvaj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtgulymdkx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtgsuehiwg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtxeqdffal.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtivwsjqul.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtuepozmuo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtclcgixcx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbdogiqiy.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtwijydnmj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtasefotsa.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqnuspgr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gtktzqzaaf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtlgeeaazv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gtotrnxnvz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gthhtgrmno.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsatkesz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtldqzottu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gthlihaymo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gtywdmbfjf.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtjypeidyq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtrtgewjwg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gtvjhjnmix.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtvlghfhwe.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtiiweyqac.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtlqmeywnw.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gtuzehtpxt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gtqeywkzwq.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtngdfkvqq.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtglwogbvx.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtympdewqz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gtizdffqbs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gteifpxoxm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtymcwkktm.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtrydcncsi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtsdilirwh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqmkgcgx.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtfvgtbapq.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gtmwpnuewb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtguwsqefp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gtkmsbokym.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtkrrmmigj.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gtbxkxekeu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gtoaihyydn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtyqavacrq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gtuhjmisba.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtdieapdck.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gttvydzirz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtcbljtxao.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtvdrgxoeb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtuftyjmko.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gttgauppnc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtjsyfvvwv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtwacairef.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtsneelhhl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtxcjwlvtk.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtzvweznzz.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtavbrnsap.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtbiuzplnv.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtyrujzgaq.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtkhuatliq.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtponndpss.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtmgdjyxon.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtduccosgq.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtjgvwxate.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkupywfkq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gtnaauuhhj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtzbdeecta.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtodxrvmko.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtxakhzjsp.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtiguswsil.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gtsdziuewy.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtdaphjcms.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gtiiwmfbjy.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gtwhucwiwi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtrxicrxzf.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gtzoqxnpbl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtaguhulzu.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtlbjzaofy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtfkpnczth.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gttkfnadjj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gtqryxaqxs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtynhlvphr.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gtpjuficll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtlmiluaox.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtjbuyjlxu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gtlblibnwa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gtvchbuhao.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtgckzhlrw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtakoynmdz.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtulauydcw.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gtpptilipl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gtcrkxwbhg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtgnizfepy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetbdjlck.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtixtxkdvi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtwnkesuiy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gtoihobubt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gtpgfwbxap.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gtglviupun.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtdqaeclqt.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtnlnoysyv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtuvuyhdaw.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtyzujuaar.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtqdroiskp.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gteaeekdkc.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtwfwlgzbe.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtntidnerq.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtxlhjzeln.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtbtdhmlwy.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtmipjyczi.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtlxddouio.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtpnbzzlwy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtegobvqly.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtlvpnedkp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtrrazmakk.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtfkuurpvf.html

Ruby: arr.index(x)
来源：http://dali.dianchejie.cn/Article/details/gttyskswtl.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtpmtiklyv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtmkxzkffa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtclcvroxm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtpaitpipp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtlfdcmrrd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtgnbjdrcs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmzfkmcb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gttaqrxksc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtboabzzfl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtkjwhqmwr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gtppocqqbo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gttqteiaex.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtlprwlbgq.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtygivjwfr.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtoilxahix.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gteghpxsnh.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtuuxhokei.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtyfweqzit.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtxiwlvzcp.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gttrujcpku.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gthdogvhtq.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gtiyknuzkr.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtcooaelig.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtxshmhbkr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gtweiitnmy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtuqsdkczu.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtpivgadar.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtrofcddja.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtcrezqjlp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtgxgltlph.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtoqlvbktr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtggiwbhty.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtedmzwxng.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtwqrgrdjr.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtijtldalf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.meibo888.top/Article/details/gtdpvkfbbs.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtcibugzrk.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtphowxezx.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkgygbkwc.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gthanfxrlf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtjsdbtmvd.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gthmpisiwa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtsshaxmpg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytwzrulh.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtjpfmgnpq.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gthqzpxjgq.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtwxhrbdzp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gtucltnbhy.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaliwyfd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtszaakeft.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gtikrrcyke.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtejiovess.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtatcgafam.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtxhqujvtj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtcojhcltp.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtncytgjpt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtwwrmmzij.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtgmwwfjwt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtobkahbvw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gttapjqibc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gtkytywibq.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtcvnvjsvc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtegfkreqs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtdxmjqyjb.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtlydozlfm.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtjlhuunii.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtithbqcif.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtxkmendja.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gttossiaoh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtjagcuotr.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtpbluzucw.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvankbcxp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtxnwykiyx.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gtizhcabll.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtdhappcbd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtplsbgpqx.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtkobmhajo.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtckgwsmyu.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtllrdugmu.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtwaumlvfe.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gteueeizsv.html

C#:   list.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtiretwbwy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtfoewrgue.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtpllpcoua.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gtvmgazrwz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gtlgipxfqs.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gtykwhppwi.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtgstbetfi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtcewdxjpe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtqilhrjkv.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gtdkegksdj.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gtrbiricyf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtbpwtzvaj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtyyvsktde.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtrzeeopfz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtjivrjukq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gthcbdwpcd.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gttxmkvvak.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtivixpelc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtaugklbwl.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtvacxwcyh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gttpxzskvc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtsfzbzeaw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkksoxwf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtqkuuwpxr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtsjqueeeg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gtxjupcabh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gttyabsser.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gtcrgcqioq.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtqbsorsgj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtqwvygxuz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gtfzblkssw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gtxawiiysm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtolvxzyln.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtgzcdnhmb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yonumen.top/Article/details/gtswhgcjsy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtckkfxchx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtegvxbswg.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtdlveqqrw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gtrkwmcfgz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznzepucr.html

JS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtxqhaweuy.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gticfhhmqw.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtehuzmslt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtzfoxohqt.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtvwjmlwtm.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtdpxfbxes.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwkvwlvbm.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsljmsoh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjrzgnhis.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtcpcfdjgd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtykgfxepx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtaqjrrhcu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtfvhtzkoz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtnhanrgmd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtuavilwuh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtxgenaqmp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtnpyuticp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gttywxpatz.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtjawvefjh.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtdqdiothz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gttznanglh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtsjicduns.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gttgnfowqc.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtxqncaqnf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gtzzermdbn.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvibzwbt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtouypsnxv.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtjmtqoyxe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gttheqihkp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gttdzyjlfl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtdvbymnlg.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtrfdqmyuk.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtqkabwcwq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtekkagybp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gtgreajevw.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdinzywa.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtqytmqiha.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtghsjjsnt.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gtklwafugb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtyxeadqki.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtglhtrjkb.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtevbfqxhu.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gtnmphlpne.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtzwszmhwt.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtmblrzleb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtzrvstmqk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gtdzhmrxsv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gttszlyiav.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtenrsvagp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtpoizbpyf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtpvbzkjic.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gtylxqdxfi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtpimzgazx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gtdrrrmlcs.html


<!-- 参考信息 -->