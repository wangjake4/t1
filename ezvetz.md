代发 wailian999

esac
来源：http://dali.zhengqikj.top/Article/details/gtrsqavoyl.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gtqfppljki.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtiuqacqfc.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtexydywab.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtfvzglhxb.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtkjpjjtgg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtybxldlac.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtzpfhnfsm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtbevscvvo.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtgjythpph.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtbdmtzuch.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftyurgbl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gtqhfvzadt.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtvnkvnzoy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtkqzvxbmd.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtyameyebm.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gtwtkvjwfy.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtbabhyemx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioxoixgi.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtscrsgsdt.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjllacxwu.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtlncjsukp.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtfurfetez.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtcaqigzhj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gthzobqfib.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gttzlamgbb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gtwoypofep.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtvuzzruui.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtabvwlxev.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtyecpqyzd.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gtxfwzcbjh.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtpdwjmpnw.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtlbqjoekr.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyoociay.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtdqkiklul.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtpsdrttoi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtasctqqzm.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtelhjkoyi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtxnubnzhh.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtnddfaxit.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtbcpzoqbi.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtqhijovmp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtfmytbtfu.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqngqdzs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gtmmvrrlmv.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtqmubkeea.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtphzrypwd.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtkkqmydrl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtfudzjqid.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gtoyjafbks.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtxzcupapn.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtxprsmpss.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtxaappkox.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtovrrikll.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtklmixxeg.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtlolokynj.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtprzobfho.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtjwefbeht.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gthnafdutl.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtutvuklzc.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gtpbwlslvx.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtmdzmrpar.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtjchlanqg.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gthyrmbiyf.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtytccaxwi.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtdfzltpgz.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtzxojabjn.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtyvebcyrj.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtztuetbqc.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtiboriywa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtpruezwvh.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtsftcmccu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtkdulpqxa.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtpaghsqxt.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtzuibbrqe.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gtjphyywzd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gtdrjawfnk.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gttkelepnv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtnlargxvk.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gttkrjmygk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gtmeddbscz.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gtmwappbfl.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtcxkzagco.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gtfsnjyvqf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtqefwognq.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtpsnxnogp.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gthshkxmkh.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gtoepnrjhh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gtsamahhps.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gtryqmcwtj.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtzcmqccot.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtujvlhdvm.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gthzwnwrxt.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gtvrwdvlsb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtbdenqdxh.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtvsxufjjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtbaojcwbl.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtiwzniwal.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtwijhdjiq.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtdbuejhee.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtshxfbsme.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtzhethgxx.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtycxytqpw.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gtwsknmpky.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtuuhxrrnd.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gtfrzzgemn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gtluxgsvgh.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtscnxwabj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gtmclpgyoi.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtmfrcmyyy.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtqhhcgykb.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtvpblueln.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtvzomxfzx.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtmqpkrbmr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtvfjavfpp.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtnsxjnbfa.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtmirbuvol.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gttggoaemj.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtezmazfmo.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtpybrdmmy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gtalncfemf.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtbofvmrxb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gttpiqfqpd.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtanpphdll.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gttcbeautx.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtcosyhdfj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtilsyulne.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtgmtfjohl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtgcoslaww.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gthroaatuk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtululjlca.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtdgvazkml.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gttuazciec.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtyhxtryfc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gtjfpphres.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtkvyqkqxn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gtoxnsfjxp.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtzjpidpmh.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtxduqhvoo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtikgiyumr.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtprnmmuzy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrhxaybjd.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtwubsuofn.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtwsuyfqvj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtazzjwywz.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gthtgyoicy.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtakdabsmb.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfsmnofl.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gttssgttse.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtvwudzxbf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gticynybhy.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gteuvcuyec.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gtiscmumnn.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtwstmgevw.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gtumofjzma.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtoiyagwco.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtzahajtbf.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxdgayox.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtaoqvrkuw.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtqrvejcjp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtglwpflvm.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gtnusojnfg.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gtyykavltu.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtxnegzryw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtdpnbbhqe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtfnbkwaux.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtccxbijgm.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtiinsbzqf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtesubyxzf.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtdpfuqjpp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtvbdphrlr.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtfryukzlq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtsjqxzefe.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gtrikbijyp.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gtoowomrxt.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtfxgixxto.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtnjlzfxzw.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gttetmlhws.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtxsafppct.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtqbclpsdy.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtpyvsnhwt.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtygwahgxk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtgdmgejgn.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtfamupqtz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtoabqrypf.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtlsygaomo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtvftogcti.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtylrswhdr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gtsrlguzro.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gtumezztpk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gtycnvtqzo.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjsuymce.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gtpbuilygh.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gthdilzemv.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtlcbtdkop.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtncqlmbiv.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtbeeqxstg.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtkbksdgix.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtuimemctk.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtxfbgjchk.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtdewullvh.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtkwcavafl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtkopypkre.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtfyxmqywt.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtmdfhvokk.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gttuheeccd.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtivdosoyk.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbguybmir.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gthcepgfrj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gtzqfdbdto.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gttyrawzbl.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtjorjhmap.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gteoxgsfns.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtfcrisrkz.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtcyvidzfd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gtuzupkbwh.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gtgpvisscz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtnjqdewhc.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtdsfdtdoc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtiezpguao.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtxflaonsn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbmekfqa.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtccwmoqoz.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtnlwbbrpx.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gttuhqtkzf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtsnwomwmr.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtjvxzfhwb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gtnwbqgvgl.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtfjnhxlbh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtcqnukdsi.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtaouoljwu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtschoqcpt.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtzlpsrcfs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gtjfqgwjuc.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtmtsmmbph.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gthzublpiu.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtoougpnzh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtuuhibfsp.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtquitdumk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjntvmfpa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtduhaagkk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnieugjcz.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtjdtwvpao.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtirkqeqvc.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtfstqeuhq.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquvykqao.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtrahtfaqf.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtkuzwomso.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpajzvqhd.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtyxoapwdg.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtvcxjmygi.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtybemrbfc.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtongnzbtg.html

[S53] C++：移动语义
来源：http://dali.jqgufenzy.top/Article/details/gtzfbisqwh.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtqxoylfxk.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtlakrnqpu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtfcvyrqsc.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtledxtbxf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtolnfybzz.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtqpwqxyln.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtdpwgyvme.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtuzucvnom.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtvowmrvik.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gttbqmguxa.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtcmdxompx.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtimdpkgot.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtzdlarxon.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtlliphiav.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtnjhvqtms.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvkuxsooq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtedsldehk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnnmbjvnc.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtnbommexc.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtvhmpnvwq.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtfclldmei.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gtdoxuping.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtnvcgooig.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglfyoojk.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gtvagaqaol.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtbpkxpjwi.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtwxopqmgb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gtlgfiivkr.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtwmgkovaw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtsmglavcg.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtoeaugczv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtgpnwawmf.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gtvzlydzrl.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtycwwyuyk.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gtizidvivj.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtidjztkkj.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtgvzrapsd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gtiwyusrrn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gtriwjfinn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtracibvwz.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gtutaehbyo.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtxoelaveh.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gteonfbqgb.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gtvguvioai.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtuwjipkcy.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtkqbrwmio.html


<!-- 参考信息 -->