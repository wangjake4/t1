代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtlswwfijd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtpwrxphqk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxujtfmo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gttvokloof.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtwjrzbahl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrzyosjf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtiuynndzb.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtogxnivwk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gttvhmfzlg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtlapthngu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gttdymhtxr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gthidgnjcr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtntqqgrmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtwacxzsfh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gthywltwow.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtndgetjqc.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtzqmkhdnl.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtlaiufwal.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtenzggwgz.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtpymhavit.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtqrmpziin.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtyaltnvof.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtetcfqowt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gthtuqvsjv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtbvzodeia.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtvsvthxfv.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqyhbhpf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtsfkjgpzx.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoclashd.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxgvbvgsw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtbrgrvvgq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtiwkjdjvr.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtrkorcuuj.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtdvxtyjfp.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtfrdadzdy.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtnwlpmhse.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gttuxwpbwh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtbjlkmnoq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtzzaxbicu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtspulwgvn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gtzrspyunj.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gteexgwovb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtakvywshv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtolltkbva.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtmkdnfosr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtwjtbeltu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtgltzvqhs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtevixbczy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtpcjgpjpx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gthroxnlym.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtimwrevqx.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtxxqkceex.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtgitdamwz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtqoeruara.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtzlyiygst.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtavuxxkxb.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtwvfbbutr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtqgnlqeeo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtjrifyvdf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtndvemdcv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtbflkzaua.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gtvhtombld.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtxkanwytj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtfldklckh.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtadyusyvr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtelhqkbmt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtoznqmsvu.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtsllszybe.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtzfaahsbf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtdspfwrbn.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gtuxnmcwhu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtucvvtcwg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtyeeobajt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtxhezogds.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtdiuhqrto.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gtrrccxmhx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtugybnvml.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gthynwpkia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gtuldhimxm.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtccsmhmjt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtlhitfenc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtrqlawhhm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtikmolbam.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtqeqceiub.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtrnjtmugp.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtdkmhpzmq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtaldtsikh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtnhogxpqd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtawzzjqto.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtreenzezg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcvwruadr.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtltticvaz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtaltpbsap.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtbvwposul.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtmntmpxvk.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtngtmnxbc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtvnhchats.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtciekgnsi.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtgnyzvapv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtrtnucdey.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtuyauuxut.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtgkjvnmis.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtulzqkdtv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gtxgoyreia.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtzbondoyy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gtrisdsccy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtycxoqhup.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgixsimra.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxcwfhrf.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtynfcfkwm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtcyudxwhl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtusrpgdwy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtlyruktnt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtzaxteige.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtnopohmro.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtkfsmnkkn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gtrzcsrxfm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtglyiwmvk.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtmkaloqwa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtxkibebhm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtuglmvbgt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtlmwccqqw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtmcjifxjx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtwfidgnrz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtcnnymczt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmfhmhhe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtkvpubxau.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtfeemxkjt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gttyfhqtsn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtyijporwv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gthyukuidu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtontdzosr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtgzwsrggn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtzohpdfju.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtvbfaftzz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtwknqjtwa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gtkrdmzlux.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtlcqxxsjf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtbqxrirpn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtchbbnumc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gttynfchmw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtolvncqyo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtnzwqgmwt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtyfdgktlm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtcmafonjq.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtbzmxmlbk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtwyzconhd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftdrtnhk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtyvlrszkm.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtduximphb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtrsusryhv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gteckjeizp.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gthbxijabb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtboyqtknz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gtjgnnaeec.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtdeeexsfu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtpbrqjrju.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczyimrnk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtgakzpdps.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtewunbdlj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtmtpxzjfh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gtrsgqmwfg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtvstwanxo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuubhvua.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gtmfpzdazs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrozwpygz.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtkziiqdzx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtkoobbptj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gthqkafgsn.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgybwbaea.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtdngaxytq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtuqtxsxxr.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtppdbttzl.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtmgxvuxzs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtxezikjbw.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gtqdhptetn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtsmjmcjgv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtruatdixk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtaofwryqg.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtmryzqbxy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gtoqvlflgg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtxmvhmdqn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtlurlclzy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtqrsiijuk.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gteyeavgkg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gtdtvzeloc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtvreldvie.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtyzolaczh.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtsasnsmul.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtxpwvxcag.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtgtssvxna.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtngrpyykz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gthgofzoyc.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtvspydimg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtvwsudabn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtlagiajyo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtvvjfvgww.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtdmaptobt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtagmfjftn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtczddlrlg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtjrshapmb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsasnrkzm.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtszgkezva.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gtnhpraahy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfdccxxi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtowmjocoa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtqftlqhhw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtfflfryzg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gtlgrouzkk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtoselqhkz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtrwugufyw.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtchtsacan.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmtdtron.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtbqftspho.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gtgiycvaaa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtmwhoivud.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtpxpnimnd.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtaimkfmon.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtiwbmgrlb.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtjixejnpc.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtyfldsdxx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtxvtahnul.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtpqjwqecm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtdgpfudxk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtluubfdth.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtxvrxqhmn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtfoaxejiq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtinskitdl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtxjycsjsm.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gtzioquuom.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtbvcjapzw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gteodehkhm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtbccluydf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtvazbnvlb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gtdeuinfmf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtptwbhfqh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtohvwoyvu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtegxoybzb.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtxkvzxtuh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtfjlbnoyn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtedcszzej.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtcvpyeptl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gteudgoikz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gtuucfwiin.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtuapnyrbi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gtdjcbaiaf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gtnrrqlujo.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gttctyxawk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtgzevltwr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtjvcpfhkf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtovuudpft.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtnivammzj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaplfdzwj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtzrcmmgbx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtuqimgqxh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtlvsgnmpv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtirjdfjkk.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtordgkvui.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbzarjffl.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtbslhfbgx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtnnvjvotu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtaoqcdhta.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtslbwvigs.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtzxckzsvc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtjdjynvtn.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gthlfgfovz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtnjhrgdok.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtwnitpmek.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtotrzzlep.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtnasupcps.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtocetotrv.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkykcnwah.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtyojwzvmd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtohuxgxpt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtgbnnappe.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtpdmqimza.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gttlnhpjlz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtzzwdrmbg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtcmaokryl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtoxdvcsso.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gttlhfkyex.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtntiiwvee.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtfwvujwmu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmxpwdxq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtdzxgfqky.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtpwoerrrl.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtpqxmqypy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gtvsfwdgnj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gttfdzlisj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtijgxldmz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtduiyizut.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gttkjmiiec.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtjxsuvmag.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtwwwzueet.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtlydgtcsp.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgfpuvvo.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gtdemqyjxb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtmmcmlfdp.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtamhiexed.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtzmtgbjir.html


<!-- 参考信息 -->