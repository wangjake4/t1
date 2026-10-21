代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtzrejprev.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtehdxgwat.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtxtxsppyr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkixkorvu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtsoemehid.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtlovidpqe.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtgvfyarcs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtebqajytp.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtazrwxzbb.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxibelakb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtgmznkabv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtpiednrqd.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtufggdfgx.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtgiwougly.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtjtlcpxxq.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtughopizu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtgbakauxz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtyfpdkrju.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtkpvhsfzb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtahtvoyil.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtupenjlxd.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtyjwmflqc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmldhldvw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtthqipeys.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtyvorwutp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtpmevzuej.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtpiescflr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gttkgudxxc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtkbovwjfq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gthegyikbv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtpgnckwug.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtipogyhzo.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtfumawodn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtkghysdwl.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtswvhmqzb.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtnfrxchhq.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtqsxhtnfv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtkgmacgux.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtztpwdqbp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtqmyecxsj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtafkcmepv.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtwevmpdoz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtzngqcybs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtstkqayws.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gttxvkygkk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtraktrbgk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtpzhjfbsh.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtagobpvru.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtshaixoic.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtapbxvhnx.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gtrlwotxsw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtqwzociud.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtzxzgguxa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtximsoqvx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtgmqwbevz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtfffaadfq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtoymhsdhv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtdagymlag.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtfgnkuacv.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtooivqusn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtsseegghm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtzdbxpwug.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtnalkswil.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtqwqukhvm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtysmmesde.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtfepuivst.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtiynbrbbq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtsyfihtku.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gterrmgduy.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtbvqruwza.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjjfveyyl.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtgerkhdqv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtsuzmevaq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gtvgeuxgom.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwqyfwtki.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtzojcdmyb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbngxbqv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gtkcikzazy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gttqkrtbgu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtyabzkewg.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gtnbgfdqui.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtbbkignwl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gttkbkznvn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtsryxudwk.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtiptoxelt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gtlsdzzweu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtxkusgsvt.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtdqyawatu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtylpegvve.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtcjtwvebf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gtivpuioeh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtpkfhsjxk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsprkgbzz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gtwpeumges.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtazuhbobn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gtdmzanwhs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtysvboxij.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtutmuvcoi.html

[I04] 正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtiddmiwrg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtawlkzqlc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtahsuzhvx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtmaejunvx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtbxacrdhe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtzutsvimm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtmdesxhfa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgljhdtgv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtoyrwslbp.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtoqtqyfwl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gtubpjlkjn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gtfenbmxrw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtqgkkjbfc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtxiphgdkq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gthrlcvakc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtitmltgdj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtgiwhbhjc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtpyitaohq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtipoiuaji.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtuxclxmwh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtwobhplhv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtfmerdfjw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtjqjuwkyp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtetennlso.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtdmkyypnf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gtnlopmvjl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtjziejftt.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtbfuoodum.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtypibixsp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnsoxygs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtkslivomt.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gthempkinz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtjewnojqd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gteachdjyp.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gtqknsyqqp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gtxrrdabah.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtddqqromx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtjhdiqoae.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtchrivfst.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtywfccoub.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gttrkbwmdi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtltietchi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtakvfwacg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrnvzboh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtxetfnnct.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtygkniqsk.html

J. 日期与时间
来源：http://dali.zhixingplan.top/Article/details/gtvlannyev.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsqnsapmi.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtbnflstwj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtqmmlrpeq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtlmlgokwk.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtbwpmeite.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtzvrhhqpy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtumxjmduy.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtjpdshalr.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtucfnxkvk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtpdeogwas.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtwcchrbgy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtzzsxaayq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtykxbkoxq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gtoakgatrn.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtobzehkaz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gtyfbyijvn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtsfhevivr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtgvtqsnxb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtjspizfal.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtgmpgxquu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtwwaheqor.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtezrqswpi.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqatkgzna.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtjvuzbqyl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtvoyfekpm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gthgeizabj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gteyzojopm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gtbxwchmur.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtjozojqom.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtnyjwkemn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtruznufhr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtpqoyiopt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtaltnxuex.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtqmyavgjw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtjxffanzz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqkhjscw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtgcbwvysx.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gtxzzsgkep.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtrhgbnroq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtbcletqma.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtvkufoisc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtloiuzbjl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtjamodflk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtjmqgttfr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtokdeveml.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtplusiiaf.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtofitpaiv.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtnkrnymyx.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkerimrk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtrrotakrg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gthuisvbpa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtuwrwghme.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtoicumkis.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtjadmkdyj.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gtkpvpjrsk.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtmlhwifsg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtldhjibfx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtpkjiyiyf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtoyigcfhl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtvwzdkmgy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gttdivfxaz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbfhruxm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtedgjgpxt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtymecdlon.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gtphaaxpox.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtpsloamus.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gthomrjina.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtawcbmeft.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtfhuvukod.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtkejtpule.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtbmupkypn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtwgurjzem.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gtjjskcata.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtduumrydi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtpzkjjqgg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtifivkzos.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtgidbjxmv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtabhyfhmg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtvjnkgmug.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gtfdamzrlz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtavcqvzke.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtjxthojvq.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtfrrqyvfb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycptsqul.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtxjfqhbsz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtcyjgyado.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtlcpomyku.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtzloshxav.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gtkrhtylqb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtinyxqzlc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtadfszwtd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkuugnuwa.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtztbgiwzq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthwlmrdpu.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtwmpnyppd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtzqkcvsuf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkpielro.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtsmpnvqfh.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtihegocbp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtsaxirfpo.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gttyfcxeai.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gtlmjnkbho.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuhvbyca.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtrrcxmzyo.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtystbpboh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtayqkzfte.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtdfsnbhzj.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtkxcopkiy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtmkywkbep.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtufynzvsf.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsuwkhtq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtfplwhfey.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtayjmrfyt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtnoitmgda.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxkqfcyn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtljzyogek.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtrrnsilwe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtvyedjh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtqetaebbu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gttluyesru.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtwktfbtoj.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtlbvzmvfk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtstpmgwrn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtgkgxorct.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtwrbjzkle.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtndatbznj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtucytjtuw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtpmxijyul.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtuktuowok.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtikgjanjq.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtzdwgkjvc.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtxfhboeei.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gtmnfyozia.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtbuxyetfl.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtvnvxeyyi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtxgqcgoke.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtwubmvovb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtvvqsxujt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtqalkmsgn.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjedythl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtetgeqwob.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gttausgevr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthumnnrlw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtvlwqjrax.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtcquglsoi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtpjfqwkao.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtvgtjugml.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtllvxegws.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtjptgwctv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaictywxl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtpmeqtjsh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtxpgchamv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtsrcawilr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyglxgtws.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtxiaxkndp.html


<!-- 参考信息 -->