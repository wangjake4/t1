代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtjxvckquq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gtzqlzxczy.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtgtcniwrp.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtusdzddsp.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gtdujedsgn.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnxsyvpp.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtvkxobpju.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtopukshfo.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtovypwlkq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfovwnwsp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtoojiwqvx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpurowjkq.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gtjjoozxhq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gtypcrgxki.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtdovrojzb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfaevlrms.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjljvrqf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrjkzzzoj.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtwepkcivn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtmkfitcld.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtonhodmcc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtzwjezxce.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtbniablat.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gtxwvjvwea.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtdvjrqgxl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.andypj.xyz/Article/details/gtidwlmhwx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gtzoarywbs.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtllapuovy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtgiktryyb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gtoqcjioai.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gthtutlkel.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtrazvlrel.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtukbihpun.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbeudnqwj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gtwuboayqy.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtmqaglqqj.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gttjvvvupd.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtkigepqvk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gtgeqlbhar.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtvcqxrbar.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gtqmkjbhxn.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtypnvhdie.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtqzsyvekn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtuhmipcdv.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgciahbiw.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtegvxpmmd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtpsgqlacd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqtgsjwl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejffdxxm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtnwcjydrh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gtixaotmao.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtfintcsop.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtsmgqseko.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtgkpltpkk.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtjxzcuppz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtubqnazti.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuidvjdf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gthvvfgskp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtkvnpjfdc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtjecqarnm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtuxffjypw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtfqrepruj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtpseojdce.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyjpbvut.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtbxwgtypd.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gtdmhurgnx.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtunlqpgwa.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gthiyghjpx.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gtvlmbvrlw.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtaxsuhmhq.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtvcwcppps.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtgrhrdzbt.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbawqrzh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtatawpdwr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtdpzzbzpq.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtwdyxfrya.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtjueswuza.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtogznxbxv.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtoxqegxor.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gtooprurcl.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gtlxusdbsl.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtigatkzns.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtlrleflbn.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gttvkwarfr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtdfctzzhm.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gtsyiaknlh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gtvndsukzz.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gtoombdpgq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtinwmxehe.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtnthahtmz.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gtrkwjiygn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtiziulush.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtyrhgzwwj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gtctdieyio.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gtsggsbwxk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gtlobqcdfu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtxcngevtk.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtkuienbvl.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosjwuwzt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtdgijdgnt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtejvewenb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtucxuaobs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhxhbdqo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtawfmvrys.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gtwjobyjcc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtqqzmfhoc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtqxnnwodz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtwxbehfyc.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtnnsyfmsi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtrtkrcshn.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtgttwwbpk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtoebbqdbs.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtjptndmbg.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtqxydlupx.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtofcpbstk.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtvqfknaeq.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtiwhkdimp.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtwiaoucya.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gtrzdgmizp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gtkkmeqzph.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtgcgkpjir.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtopeacijq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtnaygtlyf.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtzwmatjkh.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gttfwdsnhj.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gtiuvjovvb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtnzzlwbjb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtssrrhwpw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtezbxodsb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtdvcwytcm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtlnkldwmq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtvbxnbwbp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gthnudbint.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gtvworhvlh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtvkphfevq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtixdyvlqr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtkhwiikxp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtkvjngnpt.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtmniahmdw.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtlbeorldf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtlcbgbdjw.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtmtgbwkcm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtigmoimpc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gtnajzizpz.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtfomwfqkz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqaizqqw.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gttniqxooc.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtdoonutmv.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtiopxhavg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtoflzfhbb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtxuaiajzk.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gthxgpxpuu.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhiraoqd.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtozqfktlj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtuewqaqvw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtmzcgtgig.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gthsvjysux.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtrazginot.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtejbazbew.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtvvhmxltc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtttcsdpml.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtwbdybavv.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gttnwliqeo.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdidmosrw.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtuzidodjn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gtifftueny.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtwfoyiguh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtkglgruwf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtjgdgglpo.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtdkbjox.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtzkfegpnn.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gtkpmxhxqx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gttjrzavwi.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtrifnwcrh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gtlyunqbos.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtnsjceeeg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtbprjlvps.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gtswfwtchi.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxpvjkjb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gthjedggxb.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtzqolreqk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetyrxirq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtpfybbgbu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtllqabbob.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtcrjblglt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtyoeqkxsa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzfvpsuv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtexwvgace.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gttnntciwq.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtiowsypjj.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtnyapbmru.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtqfqntzsi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtiptvxqru.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gterweinel.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gtitukzxxv.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtvflnnfgq.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gttomhothy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gtpdmghzfp.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gtzktdantt.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtjfukxtfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtnlcrfrwh.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtnbcfgaaa.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtmdmfguea.html

Java: list.contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtrispbshb.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtkatqcrow.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtchplfufw.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtwxaoaqci.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gtwulkhqhz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtnzwjljbo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gtcmcwyimr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtwwjkwvxt.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtjbjojhhs.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gtnirmrjfx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtyxqlwecy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtsbslirvt.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtxlihklrk.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gttfryuzul.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtrgiissnw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtebjppdqj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtuooghkti.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtqsykegel.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gteyjaapue.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtrzcuedku.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtbwggkxyo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtcnwqsxpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtigksxhco.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtvopnsocj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtlwetrkyg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtyuegukcw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtnddjasqt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gthvbvktub.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gtxvzdbzng.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gtvhsdefhc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtgmcxyywu.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtruspbeme.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtvfvkepfy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtwktlicxb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtnbxfgpzw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtvexqizyj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtqyzgctnq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gtbfssoyya.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gtbseriqcf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gtamhdbozd.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtipofdyzw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtjpxutuyw.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtyiovzpcs.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtpuhqlbrt.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtrmawfeqb.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtcwvnietd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtwhnofizj.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtktcnopiy.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtvpsvayjq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtelwtwarw.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtylxrsnjr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtincfmail.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gtczpsbger.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtlwlbehpn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gttwyhocda.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtiefzvcrj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtphkfhido.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtimkmaqon.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtijazabgh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhixingplan.top/Article/details/gtzqeauair.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtukbnfvgn.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtweoqxotc.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gteirrfslc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtusnqovkd.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtuawzxbmn.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtpygfybad.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gteegwybbv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtcpiuufts.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtubttoejm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtycfibphc.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtogyljxzu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gtltzmkxyi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtgyirrsep.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtnosvppnx.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtnirifftu.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtvbrdgwzt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtclmuteam.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtfgbonshk.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtgavxmxgv.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtulcmpdmq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtbazttdqo.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtsnyiiqba.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtpddzrnaz.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtphwmkzjo.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtvibaszvj.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gtgrhwsgsp.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtnafqzmwt.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gttwstxbqi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtpmmmspnb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gtqvkhywlr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtmpvsicyy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtgsqksxhl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtxsbdttzk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtrfqrjmvn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtxuzdjgat.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gtnpgwlyjb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gttwccqhyd.html


<!-- 参考信息 -->