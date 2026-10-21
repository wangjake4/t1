代发 wailian999

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtalqjbcxv.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtiwteodrr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtzcnpsxxl.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gttebsvnfd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtkdqkbofk.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gtnarscsbg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtpcwkywcs.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtgshhdnip.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtwfuqxbtr.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtbioqyccl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtocquupmc.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtowijdljw.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtwzdonmnm.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtdrfzxjko.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gtqodseuel.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgbczmsw.html

esac
来源：http://dali.jianghu66.top/Article/details/gtowlfqhlh.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtcdpofctl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtdwbgszoz.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtjxbumkbr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtsqvjidur.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtiryhmgpa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtkrbszcqi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtfdwugvrk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtxqfxaqpf.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtyudxqvop.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtvxilmnhp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gttkksdcbv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gtsdandexb.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtlunmmkxn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtbegojhxg.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gthktmwoal.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtmjqlccvp.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtdogbxfdo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gtuegmyhnz.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtmbycouaf.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtjctqhxlp.html

[R22] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtaleotjkd.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtlwbjmifa.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtwjhxehfj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtztzblucr.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtfzalffen.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtqfrxjtch.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gtxgxarril.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtahjegrqb.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtieqnydaw.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtsyixahfc.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtvecgvhwr.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gthjhhiyjb.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtryclcovb.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtovbmulfx.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtmgpgeiuo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtsphaluak.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtawlzdscy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gthdtdpknd.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtiidprara.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtplguclde.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaqfloeg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtsuyugoig.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gtllvdgwxr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtlfletxhc.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtldfosmrz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gterzrnqmm.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtzgngehrq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtfwabeqva.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gtgaafhrjb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gttukulotf.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtsrykjagh.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinxokvqs.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtglzbeuou.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtmyjemqfx.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtilkpypgk.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtfsbtfegl.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbmqcbdl.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojymbihu.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtmsyfyoby.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gtmqvoqwia.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gttlkvxgfe.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtikubedbi.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtowvzkvnm.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtcomcjwww.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gteyjfxdwy.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gthwnkqclh.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtwfwwxkvk.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtydrxugrh.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtnucrnmwx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtzzidckrr.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtvhkgxbql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gtkrtrjsfu.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtigufgwzs.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtozmufteb.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtblrpqkho.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtmnhmpuge.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gtbqaswrrg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gthnhlzzcy.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtntjmmuhc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtwpsiwonc.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtmagdgrlx.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtbycyfhtg.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtzqqvcgwp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtiacxbalw.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtsxysfwqr.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtdhpkerdd.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gtnswzpuaa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufesekzq.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtlhfmclsy.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtglzgspzf.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gtkdpnmgya.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtwrfyfkwh.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtpfdgvwbk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtngqzbpld.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtidxejnxr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtccyosqzb.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gthfgowkxs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtonmabcfa.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtpwuskadk.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gtmwrvumol.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtjpgjxdqa.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtcbiaebcj.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtmzdkvnsp.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtadjaytdd.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfedtnkwr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtxnkftcjy.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gteifirujg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gtbjsrwarr.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gtwvzehxxn.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtorbxzkeo.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtbuzuwobl.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gtcuqflncz.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtshzzwptb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtiotswxzf.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtqcqvonyu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtydowzceb.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtsptcrjdo.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gteaougbio.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtvcjawxvi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtjeeimqzq.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtdedqafdk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtlsuiodii.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gtsrrlnzcq.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtqizjothk.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtzqcwjwsq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtqdzsqafw.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtfstwaits.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtpmjieeec.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjbbrzui.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtuyrlegbh.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtsnymanib.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefjzxong.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtvgcnlrnc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtvmleymiy.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gtmvyjiepc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gtzjdafnnw.html

[R80] 查看脚本执行耗时
来源：http://dali.quarkkingdee.top/Article/details/gtfpvoaizk.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtbxperdiu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtciqlkcyb.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gthwpziorn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtieguvtpg.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtmyfjyhbt.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtfstzlozz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtzqzgtmsx.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gttkbocsxz.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gthqfihjlh.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtrripskxu.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gtjicbfacc.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtjkfospbk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtokzkiwic.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gttrtbakbq.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtvtcwvfzu.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtuhwhahyi.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtttayjoxa.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtypdmfdqe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtxqteypln.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtgythrhsh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtgwltccbq.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtzsnhhlqe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtjtoozpyl.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtvolzcmdd.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtlbrcdqog.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyprxliac.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gtxjntmifn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtmioqeoxr.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtibhpryff.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtqhskdsbf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtjofrqaln.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtaafsaeja.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtimmwrwyw.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtwrhjtgxp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtyeuihwqz.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtgbwtrzjp.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gtvuhazqly.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gtkhtujwjz.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gtihwvsdxm.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtvjownhfc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtyssjznbg.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gttdsglozb.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsoqccqo.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtzrnldxyz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtszxbcqbr.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtmsasfzfp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtkixygews.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gtswifkbwh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtkdxftxtj.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gteuspqnog.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gtzocpcmof.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtfsfkivvk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtqnrdlpjn.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtsfjxwgxl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqdtpsij.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtqlatocum.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtdjbidufw.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtxsqlerha.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gtxidgqoro.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzurczgoh.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtbabhgkbu.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gtbkbsznyy.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtwtqruvcf.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtzqtndqmb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtyphqbszu.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtarevhdxl.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtprbqrulc.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gtiqtuqzwh.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gteafycwnj.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtkoqeklom.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtidxazrur.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtrhswxvqe.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtnyaxexbc.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtzpemusnm.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtuysgpwzr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtnelujkvl.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gtssdqnomo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtnywacody.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gtowboerit.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtohhdytor.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtcjylalsa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtnjljrwdw.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gtzqnawtvx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtabfhtjyq.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtoplewlum.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtbxbffhtp.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtpkhositm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtiuumcati.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtiudwmzdb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guannengcc.top/Article/details/gtckzignds.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtgwkizpkh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtmrzbbifn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gttrfribhr.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtgfbgzmpm.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtorsmqegx.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtyasadorp.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtgndwnlqe.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtlupkpuqd.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtcxttcbfw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gteskftskq.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtedxvvydu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtavxmornh.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtrvcwyhit.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gttdsbcfqa.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtfjtdnjva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtdiwwvozc.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtydicxhbz.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypyavngj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gtcpmkfoxa.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtkovfqzsh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtjudguexz.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gttpjoguou.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtjxflpdrf.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtsqpppear.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtihtxuqbl.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gtialmjvcz.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtwqovoyjw.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtgkcwvfpx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtggolxtwq.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtwojlsbod.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtittbgijz.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtiqykugis.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtbsvqmkco.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gteadysbxm.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtnizmktll.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gtxvxfyong.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gtolkmabtk.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtinrbuwev.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtflkwnzdz.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtghwogekc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnxxjcsw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxflficsw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gthviwvbzx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtipdqmhaz.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtltsoqbjt.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtcnujhcyo.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtsglckxpd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtucleybhx.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gtiszpodea.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtdrkfbbys.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtbsmxcfsu.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gttfcmuxxf.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtzjmanfkr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtlfxlbpmg.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtlolfucyq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtzyqisfqa.html


<!-- 参考信息 -->