代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtiklarngh.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtkwresnsq.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbdsvfil.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gteazkaxvs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtljjlzvlw.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtmcayzket.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtpnsuxxif.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtlrspvkvt.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtdneuahoa.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtjmrkyqbo.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtthfitruz.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtnyfpsjln.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtqesygugm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtpmyfdudy.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtgtffzlem.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtxkbbvoir.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtlhmqjwcv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtsgzxzhpf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtgfxosxjl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gtbvpbfmgg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtunkpxxae.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtfanvnesi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gteypksscl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtvlpvaksh.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtfrpmdmfo.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtmukquluv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtlyvppnpy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gthrsxnbpq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwudwnty.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtrgscdmem.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gttqiqawkt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtkqamjnfz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gttndyvzno.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtvneefatg.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtgqrmvydl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtnrsoqyuh.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gtaqyezduw.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtmqikceba.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtrnfmsxud.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtenavoyuv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtsknbrxcg.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzizxqfuw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtgmkrcheh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlkvgasvw.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtmybqhvkf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlecwousf.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtvuhskdze.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gttskpahmu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtwfhxsugj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtdqlcisxx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtddsdcfzd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdgmypivs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtfbsiuumw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gttmpqeozf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gteargwtuc.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtxvxckavl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtnmzgilwa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtsvxzfrqe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtwfjlzhyi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtkpatnqmp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtalyivyel.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtgjevabqe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtkycnytcy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gthwjigfsv.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtupxttgfo.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtancdhyki.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtadzxpfhl.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtgdnvczee.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtltfpnmjd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtnkjttytu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtgptaauib.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtnjygnynv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtufrmnqjo.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbgjfvfr.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gtlfdwnayz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtfypeyoru.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtkxhokmpm.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtyylxvtas.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtjydusmfb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtjadaevfj.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gtnaerrkhl.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtrwfasrwr.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtqlxllmci.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtqealwkux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtgnbmslba.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthtilxzwt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gthejquqbu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyzrpvtzv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtspfmepph.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtahocrzpn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteonflnjw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtncyqfegp.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtzgyzplcg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtsihsftzd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtwqkirryx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtsiliawan.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtddeqdgvp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gthiujarbz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gttfpnnqih.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gteqdoagnz.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtmbyiegyq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtcouaurgo.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtosrqfwnm.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtmfkaeerj.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtroeddpvv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtoskgltav.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtyrbhoaxy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtjcdgncku.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtoowpwsig.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtsziecfcg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtskyxmsqk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfidxrrqs.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gtklknbdnw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtzgqrsyuh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gtcsjbikvf.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtfwvrqjib.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gtayugnewy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtzpuviteb.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtrtaryquk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtpxzuczpb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtbymhmxno.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtrfarrlib.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtogfwkumj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtofeazbqd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtbsrcucye.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gtuzsnpdyh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtlcywgznm.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtwortpzzb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gtakbsvmio.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtzfhwbrli.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gthakobqmn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtmrqmzzyh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtytxboqjb.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtrciyesoh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtfpacrluo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtrypjfgqr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoxxjewf.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gtunjzsjnh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqhooqnea.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtyhbfkkvv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtgrwnnhtf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtzirimcuy.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtcdkhnrnz.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtazdbzqyz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtqddqiqhj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtltxzylxe.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtxkoimaou.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gthaibthxo.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpqahlve.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtumxejhak.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtyqioxzih.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtezwvbsnl.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtzzkkogps.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqkyjtsec.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtoamgeerq.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtnmcmkhdt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gttrfrqtim.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtepdwrpff.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtuctgyeph.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtycjmnxjd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gttbjivhbr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gtiqmegdsd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtxkvfmchl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtompoonmt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtfcxtvgix.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gtzqgtxmst.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtivuvqjrx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gtncafwofx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtjpkmxroy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtrcgkbkwl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtkicswhox.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtqzusubsb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtwqhobvpy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gturqfmxwj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtpmibpbwg.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtijkenyoe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtmdikoghr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtqjoqcchb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtawxsybjq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtkwopqbqs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtmkzbnoel.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtyqdlhzkw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtmvocarlc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtxudfndda.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtvdpzzybz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtymdrwwrk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtgjbnbcuu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtzcvmyodo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gttwgwikzq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtnmvdrtpe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtypkthnmp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gtiezvlhdy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtmnvfnhdv.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtxjgimycj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtwgygnfen.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtkcyepbwj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjplffyez.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtsrpupyfq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdsfkmfm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gtkzojaohm.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtydkxeuuy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtekuoujgp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtqipdtwts.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllytpdzv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtvfgrzdjc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtxqxadgrv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtseseeebv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtliupdvye.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtxxcnwtjq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtsktolquj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtzblarekx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtuxmjxkwt.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtknqzmciy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvkckovba.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtgogzpmdo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtqhjktxum.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtnrbzmfal.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtvtwbznnw.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtjvupryco.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtnsuovbdt.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtjgnzgczd.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtmuogkwmw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdruugnsm.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtgernprso.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjgyysiv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtuxwjcudt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtkeftxcgy.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuitzbtf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtnwhjucwa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtnkyurodw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtcbdfrsmg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtjdbsfnzz.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtkgstdipb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gthhmmlnkb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gtwqvckbvn.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtejrhgwwp.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtcrfwmofy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtgneqavpw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtkxebybdz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtjajzngux.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtcnqpgorx.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtxgoddluf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtzvtjpbin.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtnqkysqns.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gttwljgxta.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gtqjrauwtm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtzgkckxeb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtuybzcili.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtypibaowf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtahhqshsx.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtjpggfgts.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtwkygdtzi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtpuycfsgx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtsrwcmfpv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtdcofhtlc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtluiohwfe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtaoiqatio.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtdblbxjhd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gtplfegqbd.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtaqrspevl.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gthvllegem.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtivvfewdj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gtugbxekiv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtjetizxtg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gtufjefqib.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gtnsvcsudf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtsjmoqwkh.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtefkcocvr.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gtjpdpbsqk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtpewgxlzd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujnhhohx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtkhyxedxn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtwadhcmgt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtkpurflaj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gthtahbmur.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtfjcyjfmj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtrclpwhuc.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtrwigligj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtgygbsanz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtcgvzobhy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtaqwzwzas.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtbcjfxuhv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtyxtfzflg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtnaacpiuq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtmvhsaplw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtgxrzwhij.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gttinuztzx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtzjnzrhxi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtaxyttsay.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtbelhxiku.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtfnxekpyq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gttpfprzgb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtbhvkasua.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtnejycbsq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtkhyzjpoq.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtxupcdoho.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtmiqmxliy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtkxvjjzzn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gthshtnopg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtpbdpitpd.html


<!-- 参考信息 -->