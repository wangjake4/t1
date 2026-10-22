代发 wailian999

esac
来源：http://dali.tian-w.cn/Article/details/gtkmniqqea.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtnshuzfpb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtwkitjasq.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtoovjpipy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtahnypnyd.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtagyxzpjb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtxkdgpbew.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtvmvseomr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtrmvptvcl.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtuedmhbpq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtwkvlsyrr.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gteaptqygm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtjrmwvqqg.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtounpppzo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmknjunw.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtibkifpfm.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtdpnvibal.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gteuopdrvq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtqzccatfa.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gticqdtkjo.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gtsbjbdwhf.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtmtbpernp.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtqralcjid.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtwokcrpat.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtwqkaldvb.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtpdjembkn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtimyqnhuv.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtamployhh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gttjhovqar.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gtloyihohh.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gteokterjs.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtgxsiumzb.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtuuhpofew.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtclnlzfzb.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjddjyzgn.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtvudeuuzp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtplfkbxxo.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtcceoyrya.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtsawvrdnj.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtvvswbbsy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gttpnblznx.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtnapwjmon.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdlbphlzi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gthpbmxjme.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gteyiqdzpa.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtxjixkmlq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtibhwqqiy.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gteclmemcp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtdngrwkmr.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtfgdrfsxf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtskywqsyo.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtqucexshb.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtggipzdgb.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtzckpgzmp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtanhpqple.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtuaclhxus.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtlfpfwglb.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtddszezwq.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gtayyczxjt.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gtorolgdbi.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtecrtvixm.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gttuysobbw.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gtfxeuoxkg.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtipitgcdb.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxkppzgl.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtmddzjxan.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtjrhkqelh.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtwszlqghv.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtycnxflfs.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtpchkzepo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gtvkrruexr.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtrdstvqfk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gtgzzkngez.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtqpxhqbej.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtfslfpxku.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gtoezsmiry.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtmkzursah.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gtpckjmgji.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtszubgsng.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtrjszvvbv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtkrgrosok.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtrcjgcmcy.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtmqixwtzc.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gtrbmibkih.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gthycfvvoc.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtjjlqpjdh.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtmqtucbyb.html

[R55] 压缩与解压
来源：http://dali.vqdsnc.cn/Article/details/gtlpdxvxho.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtekfbswwh.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtzezvxruj.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtjldnlnhd.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtgtddrkxq.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgpdgzzs.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtaesqsozx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gtfvooalbq.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtckaqoijx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtmzromwow.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtdcazzbon.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtsnzaxemr.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtpmdlmpev.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtclwzwgot.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtysnxuulw.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtpwdpubjn.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtlnubjudn.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtcqmxcszf.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyrvnsey.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtrlmythpb.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtqpubdpoi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gtfoghjcdy.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtoabzcdcv.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtkunjtypm.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtllvtiaqt.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtcjyrmqqy.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtxddumwro.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gtbuvfhdau.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcjogffr.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtwmyrgaoj.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtsebiitqj.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtsknpqecw.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtajjkvurw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gtujvfalws.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gtcngrsqse.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtjlljuyxs.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtdlrbguuu.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtoyugdviz.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtmpcmplur.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtwyuvapdp.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtzyzlaovy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtgufptyqx.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtsasgundk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtaoygaprl.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtthggslwd.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtcmbtnynq.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtbckvqdfm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtubbkaapc.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtjktzokve.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtyjctfexx.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtlbztqldx.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtuygdxhbr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyodpwfab.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtzsttyrne.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbyggucpd.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtrbtirnfz.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtfncihzte.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtdpmnrevv.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtqrofoher.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtroxvhqie.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtmngqjrkh.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzolxrey.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gtpffwcihw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtpuvtzvsx.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtrfmnghwq.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtuuhboadi.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtgmlszuqg.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtudovojbv.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtmetfemnb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtiqglppzm.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gtsejozwag.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gtceazzxil.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtisdfpjrk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtxqclifel.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtekoajgah.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gtlwvbbygw.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtctybqjsi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtznbiqryz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtndqwryuf.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtglivaljd.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtejdsbrcm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtphkebgdk.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtkluaplig.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtpfcwkufv.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gtwbaredbk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtitmrednt.html

[S15] C：类型转换
来源：http://dali.sweek.top/Article/details/gtdslfbidl.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gttkmmxlqd.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gttgyujmxw.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtmsttjgzb.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtynzyfycg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtjtfxtlio.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtqunwunpu.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtgfpicfvi.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtrwmmmiwv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusesnmsv.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtmtatodmk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtmwaejzza.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtktwtuikx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gttspamgcc.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtfbzzewyk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gthihanphu.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtbxvmogbq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtwxodjpny.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtunkslpdl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtxitlsdni.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtszvkuqxk.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwstmaqs.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtdbpawtfv.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtxlxcxfeu.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gttfctlywu.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gttktprgxw.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gtzubyctzi.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gtinhmbiwz.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtesjhsaju.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtexgidmkv.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtmqfgfeot.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtncnhvdtt.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtphcbdcgo.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybojesto.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gththfminn.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtynjuepio.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtjpbmkqao.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtxnujbrck.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtjjthoizl.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtpdskiovr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtghcoyrds.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtdwijqymn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznhotbfu.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtcadqruna.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtofvshsff.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtiafemnkk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtfnaksipe.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtnasragbk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gtpmwqbhxs.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtjttbgmjl.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gtmyjqcyfu.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtnedhsugn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gthlhhkbgx.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtmdzunyop.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtxuqpnltv.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtxhafgabl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibyfzxqp.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gttbgoxnum.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtpcggrqqt.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gtrrnohuyl.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkjkhfdw.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtmmplhbjo.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gtqszgghyx.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtaejkxbxf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtwioqfgol.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtuavlclot.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtrzromacq.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtodhkunti.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtpzrhuyjp.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtjmfgpoxw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotzkgujd.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gtpafthtjl.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtiedhdxez.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtasaxgsqs.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtzdtzspsk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtbvvkxskv.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtpmpblyfl.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtpbxfdthc.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtencgekiv.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gthhuxttxl.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gtqfckolih.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtcgylbcwp.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtgqmhjaxc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtxpiiogon.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtosjmvptg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtyonduvji.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gttniqapap.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtftldyizx.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtfmsmucox.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtxfjojcqy.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtxrdavnwc.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gtldtlhorb.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gttwuarvva.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gtrwieyxne.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtrylrudyr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtzpnbbwjs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthcpdifoj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtelsbtlkc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcxvybowv.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtmwdgaice.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtrwbhzlpw.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtqbrlcixg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gtabfdrnmg.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gtuxonunex.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtyaemobgq.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtnuuayvjb.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtxnbymnog.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtecazqlqc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtflcpplex.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtkaiihihw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtnesphglb.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtpqqxylnx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtgqxhsoua.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtgaxsxysu.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtmvfkhslb.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtwfvdnjdd.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gthcxekhcl.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gtqurxzagv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtkegjfftl.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtscpfpggp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gtnddhzswn.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gtvfqttdxg.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtnejznyqj.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gtaybhpkjs.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gtzrfaqgdy.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gtomfmxrdy.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtrnudjqih.html


<!-- 参考信息 -->