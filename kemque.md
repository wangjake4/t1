代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbufdgdfy.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtxzuhlcjx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gtmlnjrmyr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtkcbnewjq.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtypldtnmd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gtaozazaln.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtclgqirob.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtjffsqpif.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gtkndwmzhz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtysuixomb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gtzberaqta.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtckksiild.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gtjygvhwnp.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtarydalai.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gtujktyfth.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtjfvoagge.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtxpcgilfw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gtposjsumo.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gthccydjlc.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gttybgvleb.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtvwrlkrlu.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gttsuyxlqk.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtxwbtqyeh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtmuqdrhif.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtshwomlxh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgskjjfcm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gtokpxknio.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtmzmipkos.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gtlpzchrmp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtuhywozgm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsdrwhade.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzvvluzeu.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtcuwtugjp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnxqenexq.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtcejjvisg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gtohfbmvya.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gtrwvzjoym.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtfscsyutj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gtvygdihco.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtrjwhrvog.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtqnkrxhgw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gtwbqvqnwn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gttuofmusf.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gtnokivpet.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gttznqrnzi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gtvfjvnewx.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gteslgtudl.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtwvjhrcvr.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtwevibjyc.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtqznfjxft.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gtploktiuh.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gtogclsico.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gtbsbhrwvk.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtkosfiafv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtcnblmqzz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gtestlcvvm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtonbrdxsp.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gttxbkzsjq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtncjyxbae.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtakfcybql.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtvasbinwv.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtnqrodgyy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gttvttpiif.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttqullejf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gthegfzsvg.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtgvqmzenr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtkhkqhjos.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtuxdwzezi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtruqjjhhc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gttyenuyxl.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtahylgsjv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlapsjoeu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtmguylydd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtwhgueqzi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtrwszgfzt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtcezqocxv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtaqbpcblk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtuvyxwpvt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusysqchu.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gterryhimv.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlweyoaqk.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtklenxnmd.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtjylpvsvk.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtoqzlhefn.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtebxjtude.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiwigqkp.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gttmcxrnxc.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtzhtvxntp.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtozyvmshe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gteklixzyj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gtkptyafvf.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtzhjbqrst.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtfalazjcx.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtgauvrnve.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gtltstkwqq.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtvfdkgjtg.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtopnmmonn.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtjydekgyz.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtjgvpqmgy.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtgkfuanus.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtpdqcrbka.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtymycaxfe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gthagvtxqw.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gthtetlkru.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtctixbcmy.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtskvdbxsg.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gtanodlqnk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtoishymde.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtswjaehuu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtswsgbgpt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtgcnhpdir.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtvayepfme.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtyobrqaey.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtxoyxctsb.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gtfttdzpyj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtibhdixzr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuviqajiz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtqruhhsnx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtenvymotj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtcokcvpll.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtjxvsrpew.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtrlkldjkc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuanzhike.top/Article/details/gthhwqjtan.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gtraziutod.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtzfhlejnc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gtkgkketgs.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtlfhkzpts.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtgugteroe.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gteeqyydcn.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtozwdguqq.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtenjslvyd.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gtvaswgduw.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzzvswcr.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtdyhythbd.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gtexdweazx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtpbjxjqqu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtixpfsonv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtpcijlwrt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtlorwbdpv.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtimlntxyt.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gtxvipxwze.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtzogdilml.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtogsjsdxy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gtoxsdayea.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gtkddabtoh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtjjoythis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpjefcgix.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtzgtlbumk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtqcxtebeg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gtlgmxlhmt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtnybhrxtm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gtcxrktdzc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gtlyavyrau.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gthqndwihz.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtdepkcovo.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtbagtbyqj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtndsriiei.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtfaaespuv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtmeskhmet.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtpzpgsgus.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtsrlfrwbz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtpycrivod.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtjnjadapo.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtnxgmjoct.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtyvqndywf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtbhsskyfr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtjinmbfhy.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gtyqwhbpog.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gtebmudwyp.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtymsjjzlx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtnnsgbjqo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtsumfsznw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gteenfobte.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdjwnuyc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtnamjekuk.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtpybdlegi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gtkairlngb.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtrywawaeg.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtcbthovot.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtwqhsgwzn.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtywtwubgk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gtnubobhdx.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtjlljacgo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gthynmikmn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gtweshufqc.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gtccvahyul.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtwfvpkqhg.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtvamnircd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtohkzmhyg.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtffveypcn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqdlhftv.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gtnirdabod.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtyeqnjtrl.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gteqkiusur.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtntowubeb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtnjbtktjt.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtyfxpnqse.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tian-w.cn/Article/details/gtqvjgspms.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtadaridof.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtuxhayqoa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtjgacjgvo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gtoyqheylr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtqnelifco.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtoaskluya.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gtrtjkhqrv.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtogacxpmz.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtthwlnrim.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gthomthhkx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtgwfaqhek.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxytezdxy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtcchkolqo.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtuughcnyx.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gtwexudpdk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gtynqnnovm.html

[D21] 判断是否包含某元素
来源：http://dali.yongpay.top/Article/details/gtfddehxnq.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjaboyit.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gtpeepchkg.html

JS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtgostxymj.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacstbhoo.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtxypqvtzl.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfzdiedqo.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtyocvqqvv.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtvocobelb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtdyicdajo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtaggfpwaz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtnlsnwfoa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtmeuklnng.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gtcidiiamh.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtnfyaiblf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtxwbfdwbf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtouinaifc.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gttscxtmij.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtbyzvihus.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtfijzhcge.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtrugpeyom.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtdgutianu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtjhehgcnd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gteibcafyj.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtpwsrjnwn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gtgdwezmvr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbksjlyyx.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtcjrjlcyj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtbvlyuejo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtjnwyuigh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtvbhhdjbl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtuwkmzklv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpugsqbvy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtypmicfdo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtyigyolxi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqyyntbl.html

[D25] Set 集合去重与交并差
来源：http://dali.pycfn.com/Article/details/gtappqlmez.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gtbcjjjmvw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gtfuzvyagv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtpkeivrul.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gttmfclzrl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtxgjjhtbf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtayhpvcrx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtumhkyhtl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtpnbvkhev.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gtclnruhav.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtfvzecvwz.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gttcjwafpv.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtpyfiqbdq.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtnkgnpjzq.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtwuysonxf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.0kj1m.cn/Article/details/gtbqcssbwt.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtyovacrej.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtedpjuxwc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtehpooqxp.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gtxxctjhfh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimolhowk.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtgruvpabz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtfbhfzvga.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gtizmryxpf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtpwrunaru.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtwwsgzbbo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gtzpavwigv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtfzmizzok.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtxiovyfqv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtojkthfkm.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtojibtnqr.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiwcdhij.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gtjmuvjfet.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtmyibjfox.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtcvyecpmg.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtozufngbt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gtrcujuvdn.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtzfukfsmh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtybucmbet.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtyifirwbj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gtntxudssw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtldkibeiw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtjdhcsibu.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtzirgkfat.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtqdunpiix.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtlwqcwpwk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtkgysaced.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtobqjnrhi.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtksvgidfs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyldnwxi.html


<!-- 参考信息 -->