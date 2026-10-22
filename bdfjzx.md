代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwksbyxp.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gt2yazjbdvx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtmkfqmc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2yxfpsybu.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gt2uyrilwka.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ysyrcrqq.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gt2hsrdvndj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2unonmsgc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2oqxkjfwu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2jyzvowoz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2pxyjepkz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2jcnsbcdk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2gpwlpgwv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2zihwxnnj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gt2dgcxpotp.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2itnqhrcf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gt2gsjjadzf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2swwqakpn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2dmmxqwdh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2tqdzgrtp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2llutcfmm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gt2wyqksmus.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2nwmgzgny.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2mnhiecdi.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gt2kjplfhlk.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gt2zlwrpfzo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2oocvohyn.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2jylltigk.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2zbmwtuvw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2owbdqhcq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucymtcoh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gt2iujdzvej.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2ktmoxejr.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2qeigsrpv.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gt2hqpwvdix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdgnruhf.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2afcdvspg.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vflstxkw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2akhvknuv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gt2gkjfxrhx.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2xfivyowt.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gt2tudqknvy.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gt2twhlrmny.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxfalxjr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gt2dulsqfxt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ljjmnane.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2ocuomjvv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gt2leiojdlx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2oapswopf.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2czyiakpc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2hunespli.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gt2tuxwpbyn.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2vmhrotuh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upwtlyzt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2tddatoqb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2dfjqsdeo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gt2bgnsctue.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gt2svugeiql.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohttijtt.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2aiqmwwkk.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2dygxwaer.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gt2lyyyksrh.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2oaehmkxg.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2rscglefa.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2blahfxqx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2lcwqmslo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gt2hgvxajge.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulmepzgy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2iitgyywp.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gt2blgcfrby.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gt2thjwxjju.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gt2npiqurml.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2vdezhezg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gt2uuuqvycp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2oawhrvqc.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gt2iwbbvret.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gt2abecemkg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gt2hhgknxak.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2fnajubwl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gt2nxgbwscj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2gagukvvx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gt2twwaafhf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gt2pjlpajyd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swpgmdlo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gt2guipwlvd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gt2kyvrptkn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvhwoenm.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gt2zonskfhd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gt2jrsavkqz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2qsyljlcg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2rukcmggt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2uowxejua.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gt2nhtqvlqk.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gt2npyjekui.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gt2uflwsdgk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2dqfdoqlh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amviezxo.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2xdzsngbm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2varlrwdg.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rupimdgm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2nilhifcj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2lqmqtlas.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2gtfedyrt.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2wyzohdsv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2fvxwbfqu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2iucshwsc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2lsidabnm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2azwvzapl.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2ueoyyris.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2yvgyscri.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2rnsesuwh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gt2uoysbegp.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gt2nwpiniih.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2crefumik.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2aljzykoy.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2nychspve.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfxoxxqa.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gt2wprganbq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gt2sejhohyz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gt2dgmyulyx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2qdaiwtkp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gt2lpffmeci.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjhqvaee.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2xzlsyukh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2gjozuent.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtvmqhy.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2oofhtfbf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gt2qgnctxgv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2vsnwkxvh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2epdbskld.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rslvidai.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2atoklqzl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2sgwgindg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2siizmwje.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2aoudxuid.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gt2fvzpbnhg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gt2gfssyjbn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2cjgfvapz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2gbhezycg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2avymnwnf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2pecjnbtu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2xzqotyok.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2ysuphpnt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2jnyfeawb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2dgisbzyu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2uyasgeob.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2dnkzhiuq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2prxrltia.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2ijkjixbp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2gbcsqeoh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2fulgsysq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gt2lnigaokr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2rsasxwjw.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2gozcbcav.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxjcyxkf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2hwerzmqa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gt2etlbskwh.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gt2csqbgrhe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gt2qhvfznmm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gt2pepblmfy.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gt2hbhappmj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwpjklp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gt2rhygxzhk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gt2ihjrgzss.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsptmntr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2hsizkmqd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2rhceqobe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2pdahtfsf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gt2xhhqwgsq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2lsbfaugh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2fhvlfqdi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2utqeflxh.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gt2tjsvyozb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2nhthmhez.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2mgvimddw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gt2bfveenrz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2cviqnnzf.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2nklmodnw.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fovpypqo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2ndrsvowm.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gt2rwjlxrtq.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2jzeegtsn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gt2zkhnrfbd.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2qjvuebdu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2dakwyqwh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyooegbt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gt2nortqjwq.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2jziopafo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gt2occvflcv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gt2lpjklera.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2dekseyrx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2uakrzbps.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2llpucipq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2nnhrbqgu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gt2ubdmukll.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2mvhjjmwi.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2wkzjugsl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2coyaoqhg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2izfaascw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2htmrotar.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gt2yetwphvp.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gt2hkitueem.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gitjpxzd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2ftuaimnz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gt2laklafdy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2sdbsxvsf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2wzikahzm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2xftughas.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gt2ucmdpigf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gt2etrxbgqn.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gt2ycncrrkd.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2soqufdnb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gt2xvekfgzl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2xufvgxoj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2wxdhwyca.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gt2klwtnicv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gt2neixnopq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gt2ldvqloqw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2njstjktm.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gt2eccigjec.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sydhbadq.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2famjihrl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2dxsaiyvz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gt2agtptdmk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ketxpzqo.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2xlgfgaex.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gt2cdvxrzzm.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gt2adxaungx.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gt2nifepvil.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htgrvlhy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gt2bzdwhchn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2kwzfodkv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2qlbtafwt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtrtksvg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2enirfyjv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2igciaxhj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2qiydhsdd.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gt2jvlbcuue.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2bhnqpxpa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gt2vayijzfi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gt2puxpyybc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gt2bmefzmuf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbpruscx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2holgnvly.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gt2atvihvla.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gt2fgjoowzu.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2kjezzxzv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gt2dcbqsrdl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gt2geufhxwx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2fkukrojk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2azsxqbnn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gt2judzocvn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gt2obzchpsy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gt2uxidjfin.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gt2ckwmsueu.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gt2vtiqulvb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2vyqtbvww.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gt2zdcgsdyu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2vdjcprrf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2ogqgxhvw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gt2dzztbfwh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2dpwedoze.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gt2cxmjmjdi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2pzhdcqli.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2jckaojhq.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gt2ytkdvgze.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2oseeasww.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ztlaedfu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2slqfwale.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2oshborpl.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2iodapudj.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2mipiypfd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gt2updqwwjo.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2rjcelfsg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbvfqqfw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gt2wmwvnprj.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gt2aimuukgp.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drmmmtsh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gt2yhqzelzn.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2tttpicgm.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2anhhifbc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2izopdxiy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2csbfynqq.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2riiqufnc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2nbcyljxo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gt2pfgtintz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2urujlvxs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtaetrvy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2fewuvcsx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2rxfthbjh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gt2acrdkbtg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2ikwialwb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2toplciyj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gt2dhrqqvim.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gt2dqzherhx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2lisklogu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gt2rlmkiqhq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2tiyfkpkm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2brtwrelt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2yoigjizx.html


<!-- 参考信息 -->