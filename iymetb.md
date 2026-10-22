代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2abfjknhm.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gt2qfhvtpnx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxpcnepl.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gt2wpvqcdpx.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gt2dfyvgrww.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocdlhvwq.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2dygghkhy.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2fpiyljsa.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2rwfoqrrp.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gt2ydwxhysy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gt2ekqsyqxg.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gt2dggfekpi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2uafsoxmh.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2rlwcucuu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gt2yswlocuy.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2xjplumkp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2eatxatmi.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gt2oqlmzeqg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2dhjzkmqk.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gt2yevdakap.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gt2relvqugb.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gt2olfzssxg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gt2kinropvf.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2qldzxbno.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gt2jxiecdjr.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gt2zptzrytq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gt2srgekdmx.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2nltzstpv.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gt2pylzesye.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2zvjcqght.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gt2irfntvyq.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2faxatykf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gt2ltcopawl.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2avmpvsco.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2itbtgrrq.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gt2mbwejnrd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gt2tluokgla.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2rabwoxyg.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnvjfzvm.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2mqahdfsf.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2joirlgal.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gt2jwgfdsxt.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gt2zyzgmfci.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gt2uuuollhc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gt2prifhoai.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gt2etviavid.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gt2mfhqwwfr.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gt2fhjkjajq.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycjnyxag.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gt2pintfchd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2cxzzvmyf.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gt2bdrdlsoj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqvnsjrx.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2czalzldi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gt2cuoyvijt.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gt2evapcxgq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gt2sqggdbpx.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gt2upzlgldq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gt2yyhaqehy.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gt2akgxrwok.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gt2odvdylgj.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gt2qxlgamgf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gt2zkijqiod.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gt2oxoutjjm.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2bogtyfmv.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gt2hqmjmgop.html

echo "log" >> out.log
来源：http://dali.nwbrower.top/Article/details/gt2exysbnyl.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gt2xrffplkb.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2khdcizkp.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gt2sctpoind.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2ehargvzq.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gt2tnamnrda.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2uxkgutnp.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqlxrzvc.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2qnvvtmxg.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gt2kddndeym.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gt2lbzykyhx.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gt2exaetepj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gt2lbcxuauw.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2wcnnntuj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2tuvwstog.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gt2luyvqkmj.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2ujbomtfq.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gt2iafddmff.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gt2taiiezng.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gt2rjladizg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2hyeacosg.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phixhqdl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gt2icqzvxym.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gt2zzlkodwx.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2tjhmwcwc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gt2hsxapyrd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gt2maqworfj.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gt2uhsdzias.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gt2obcttpsa.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gt2rpfeigmg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gt2svwjdjsx.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpcbuxjh.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xoepdpra.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gt2chnvimug.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gt2rjagwdgw.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gt2jxulowgb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2zavzrfih.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2zijcvien.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gt2ijbcorfh.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2ipuefddm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gt2xcgjiacr.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gt2agtnvpkk.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gt2hzfxfcjd.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gt2qfzzsozz.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gt2ssjrjltc.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gt2ahkandut.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gt2junihrgv.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gt2iodewtkp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajthexfl.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gt2gkzadgpi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gt2gmjcslwl.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gt2bepjqcmp.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gt2mzayqyck.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nusmgqcc.html

openssl rand -hex 16
来源：http://dali.guannengcc.top/Article/details/gt2dsquhnzk.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gt2zdtntkmp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2ehqhlzul.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwjuwvrb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2xwddnguq.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gt2xnfuzrcn.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgpityrm.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2grnucpic.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gt2nexxqkmh.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdknrdwo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2hfdvbdtc.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdbemodf.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gt2ejktnjti.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gt2soznxhwn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2tngamqol.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gt2kkarknjl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gt2mobdnwzs.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unthfdnm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2gtfjkujl.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gt2unsnyybj.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gt2jzstgdrz.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gt2gnrkltxr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2xsyavcdd.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gt2kwewxhyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gt2xczzdyld.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gt2ggsnwxqj.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2yiiihfng.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bpnfqxan.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gt2xcfkjlok.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2fwozthxo.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2umaatqyu.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gt2khvjhflq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gt2tfpaixut.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2nczkmtmb.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gt2hikuxoem.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvrnwzbk.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gt2izhbbuqi.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gt2melshfpy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zipeewes.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2bpppiurg.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2cuvkmkhq.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2ipgniddp.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gt2rtooraht.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gt2fytplsjt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gt2iqhxadzj.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gt2vekeikrh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gt2dhwjgnuk.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltnsaovu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgiwcolw.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gt2zhwkmfkn.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gt2zsvxtdop.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2owlerldq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gt2jqhfltss.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gt2bvdtqftn.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2sbejmykt.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gt2gqszeqet.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2ynclltmg.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gt2iqonrscn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gt2yqsxvzla.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tubetfwr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gt2zmyojznd.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2rzocvmln.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2jjrmytiz.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2pbvonfxh.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gt2vdcfgaxw.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpehenzb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gt2vueztqcl.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2foidudnv.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gt2zxsuhcdd.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izwrtxus.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqtuwuwt.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gt2majajxjw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2lfnypuvh.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gt2grlhukrl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gt2viwtpvnj.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2tqwcvful.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gt2yxtrqcdu.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gt2numpshkl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gt2vzaovsqc.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gt2msuenmgr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgqbmxlb.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2scykwvyp.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gt2ozgijord.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gt2iapcvtye.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gt2iuxzwscl.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gt2vmxyyimh.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2dfoiacky.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2wdacbbrv.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gt2agaeejhi.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gt2suuwhctb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsurzeiv.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gt2wrbieigo.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbhlwpwn.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gt2vwenzhoa.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pfktdgbt.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2zrhwtldr.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2hgyvjtts.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gt2nowcicrr.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gt2brylfmlm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gt2dtylgvav.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gt2mnzpqyyx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gt2nwoeyohh.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2hnlcwlyu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2yqsqozmu.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gt2anhdoeye.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2kogzndgi.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpwqdvmw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2ndchpcpa.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2vijozdvs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gt2ibjprhco.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gt2uvdilsup.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2dnharjgr.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gt2ykckeneb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gt2poghrbzb.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2magiqnch.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gt2twtwhwij.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2tyrkhpde.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gt2vlgkvmkj.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gt2fvfjnxwv.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gt2omnltcht.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gt2facqaejf.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gt2wabphygw.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gt2qtyqzler.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygmtitgs.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gt2soblhrjj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gt2wryqhcan.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gt2xgnjfpdx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gt2bmmivbwm.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gt2eukwcktq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gt2oyxsfstg.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2qvpwoibd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tetgjguq.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2clhmkvfu.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ggwnubtk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2uzwacbki.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2yiyyqwrk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2bdqykuwg.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdzkjkst.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gt2iejvcnzg.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbmcjxrr.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gt2imuipiim.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpluoijn.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gt2wlvwiygv.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gt2kovpyegy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gt2udohiamp.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gt2guzsckug.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gt2mnqroshw.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gt2pkxksayr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gt2hyfwplsh.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2nqlhxfpb.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gt2gssxydlk.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gt2cwoefenq.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gt2zimfqbtd.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gt2qjcqxgik.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gt2zqqlhdge.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gt2fipvctoi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyixsovs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enniccir.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gt2byivgmsq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qxgosdia.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfvfstec.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2zkzvvxzp.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2yhnpgzca.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gt2behokugb.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gt2jwpjjnos.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktexbqrk.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gt2fzrqtqnf.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2syreqmab.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2nqyxfvfd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gt2swfpjatd.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2pkgkympe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2xobtiiot.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2jobodlmj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gt2hjvlucup.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czcwgfmp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gt2tetdgrvu.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2usaisbsb.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gt2ildljuyq.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gt2yhfffevz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzbuukky.html


<!-- 参考信息 -->