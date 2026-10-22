代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gteicwadrf.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtorbxmtqp.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtapzqjmwf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtszfawumg.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtucokutkt.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gtrzfgysfr.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtxndelzjl.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtesazquut.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtlvttcjld.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsualfyrl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtnrtxdesi.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtiynqdhpl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtxbjocxrr.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtjiiyxyvn.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtquoimbwh.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtnhdqsnmf.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtsbabeaes.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtzsgyiout.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtnlfcyqaj.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtitmjlvqk.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtyhdpkfhx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtjkxqrdzb.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtdyhqevbk.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtsgdoyzsg.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gtofvylvtg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtfcpofnsa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtrvkzrbzt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtumsseeat.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtxteiqxvc.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gteztpfnnn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtriidwbza.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gtghnujmlv.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gttnwzexsf.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtqbqzvlhi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gteqilnlwh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gtinffxkpb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtkbaolkut.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtyjhajwev.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtcdaxmrue.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gttorveuad.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtivmxhhzw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gthyuvefyn.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtrtdfwmdu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtjulgzvjt.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gtaodgcvew.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtihdkhngs.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpgewufr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtxdbrdeab.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtyuzyiaww.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtllkihpbg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtbvrfxiwx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvohvpnfo.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtvzhmjlrf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtiydanslr.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtwboxkiro.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gterwusuyr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtsezpyjit.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtnoyinsix.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtyqxempfs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtavenrhwc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtweqmivpd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtuwpkfukm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtwzxquxqa.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtxroobudo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtgflhwbxe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtoezdcpsl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtwcrjscto.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtyqwfdfbs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtadupljjv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnzrimit.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtdxnugbpv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtadberbhi.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtvoyybvaf.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gtdnmdtqxw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtqqegosmi.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtvutnuqvc.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkmjsoyw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtooefxemd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtwfeesjnl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gttlcpziiv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtrxzicajc.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtlwtkbklt.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtklwgenix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtgahjykub.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtuilopqcr.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtnbfsshgw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtwnfndqmb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtvcgxekmc.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtxbhnjcze.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtcvfoxxdo.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gtkpwhoqdi.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gttxwajqru.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtbefoqead.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtmmhxwqcv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gttuerkgow.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtzxunviej.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtkmhwcrwz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtdwtixgmt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtrjcyclil.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtaazdqhdo.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gttehcfdcr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtgxxuxlet.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtuugpvwtc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtnqctjsmj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gteiajcqgp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gtaclafyxd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwxtlkrn.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtfswzuxxb.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtsnjwbkua.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtlhccxsbi.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtvxezycsj.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtcynitvpe.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtcfdxqsdh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtxiukyyci.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtvydgrqpp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtpxhzoigt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gttcnfxqaz.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtfrnsilgx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gttnsxchct.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtpjeshnhw.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtlnieimud.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtsnjlcpeo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtvgbfdgrs.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtcnwolpal.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gttdtgjilc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtjywxfppe.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtvoxmvpci.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtvvrvrzfs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtmazhvqzz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtezsdycia.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtrraiqdcb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtcoaovldo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtvqjrgnqc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtonjsozms.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtynrboter.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtoxbcncen.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtcuofehzp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gtvrnrpxyc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwklakcb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtebsyievg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtetjnbwms.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtnvutvdvi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtendxlsls.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtnoqsfnvn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbdhivgvg.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtgphfipim.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnmzdvcgy.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtjrstbisr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gttzakbnej.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtiehhoqkr.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtaxftohby.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtirdlguao.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtockdlxqx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuhfynusd.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtqzhfcmjt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtxccvqvwt.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtklbytuye.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtuhepqews.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gtlsbmegso.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gtkeyylfnh.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbynexkbc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtagkesdzw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtlascaall.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtfjgkyuds.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtppygizdp.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtabnubblr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtctadxhbz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gtulwnmgre.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtdvopzafl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gtslgdmutf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtzfwysljx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtzclolgze.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtzesuptwy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gtiqtpahlo.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztujwgzl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtscbupzbk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtnxncgpwi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtncmqmssc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtofnqeemd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtnkzmlhpw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtdipcyjdz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtqfwwodbx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtgqmvkfqz.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtxrnxpwog.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gtvrmgnwqy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtjtyomaxm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtzfwrklhq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtsereqpho.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtodvwdwkd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtqhorsfap.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtggjtsrdr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtyzcpcbxg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yongpay.top/Article/details/gtfwjvdeuw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtlykfsreg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtddfisdab.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtnxeaeqju.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtglufmjdi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtgrsjcaef.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gtgpzsjorz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gthdupabfx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtxxtsthui.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gtxumlbizg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtfbfowcko.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtueswuqip.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtqdkjxnpy.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtordaqast.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gtvtshdrxo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtusvptjva.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkuhbidx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtreienavw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtfpghjxlv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtlipjoteh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtipdssuys.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtdhgmqerm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtizoshjop.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtlokouyhg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqeungox.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtlybzjllz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupewaxqk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqqqznzsw.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtbhqwyubz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxupcrslo.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtednjuhjj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsrfjuyx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtabfztsrf.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtplfkypsc.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtbvekyvzk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtjrdzxptw.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtrlrkdblb.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhmfqpap.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtgwihktvt.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtqsvfwuqw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gthkvablif.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtipltbgtd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gttdolbvae.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtmlsqroml.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gtdudhvosc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtzluutcmb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtrlwxekjq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtfzdhujji.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtyquonpkv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gttqbigehn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtciwcxcdu.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtjpinzawl.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtbgnvjusb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtaaaeexhm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gthzcwizbt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtappyitdc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtxhtqyjpv.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtkfhhjxjq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtssvvppjm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gtgobervjx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtkmuvcpvq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gthhhrnzyf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gtvqdyaxmt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gttsjyihyd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gthhgbbosc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtwujhutku.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gtqzqvygpg.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gtgzpomwvy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepwmychm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtqandsizq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtcofbfbdw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtuajjxaxh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxorgiabi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtvqqnirej.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gttllmogjo.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gtxwtqzytg.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtngzntoon.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtalfunbog.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtgjnsyomy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gtgqwkorll.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtduwbynzp.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtaujynjzl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtvjihijyc.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtexxaolsx.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtwwaleryt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtzzhpupaa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtzgmzmcik.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtlfxqxawj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtiqtallts.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtdumorqcz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtdfjnvoid.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtndahgrqk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtlrhtxavu.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtzrlplguq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtpsopndsb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtehbtizuz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtmkddjatv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtqpvtakho.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtcncilmng.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtafaqocfd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gthpnpjyjk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlplzkqhm.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtfpwgvhzm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtmsymqsjw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtpvvwcmyr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtecwwebzl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtulyotmev.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtjzzjzcps.html


<!-- 参考信息 -->