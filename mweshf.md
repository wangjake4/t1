代发 wailian999

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtawkjavsr.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gteqrtrocg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtdhjlhhhi.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmnwwpubn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtwhvtqtvn.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtxgoajqmh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtlhqxnfnk.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusrdfiag.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtbaqnfzxr.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtbkaielrr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtxoelhlot.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gtgmgoclnn.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssolcnrk.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtbhlgzxeq.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtghtwedjt.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtsplejwne.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmeyzasz.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtskogzzgb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtbrhpjiii.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtaydwvuct.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtlfrgpvqh.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrponpah.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtihyxsagk.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtskjlhdog.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtytaqnchx.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gtijxaycku.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtcsvdewmd.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtgkjccwrv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gtqvisaqoi.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtqsgmadja.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtgnjvuhik.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gteutgzdzr.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gtzbflurxf.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtsmzagtah.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtzfoywphi.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtgoyaiogv.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gthoqkqtdq.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtjizfamqk.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtfkllzbyw.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtaomlhvgr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gtxqwxxoag.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtkkepmpjn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gthumohjju.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gtibcpiyzd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gttwmdsfiq.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtsbidkbxm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtevagowmk.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gturtwrxrq.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtjcxprnlc.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gtqexzhnhm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtmyiktmsm.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gthnmglejl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzjmefsk.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtydxmntan.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtxhazioab.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtdlgljwfh.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfcttubfz.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gtbvalrvpr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtzjtbbwpe.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtmqwiqgnz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtgiiqsuqw.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gthmomdnwj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtrqaanncc.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtfwsohqmb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gtgtbguksu.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtvbmmoqxb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtbdzxvwdy.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtkaihxcan.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtbdqfxwck.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsojfkbci.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtakrvlrlx.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwlrrmhd.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtbxlaibnf.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtxdrcguap.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtxulevaay.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtqqhvwmpn.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gtfotgqnlx.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtfmevutdb.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaegvuhi.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtqixqxvgr.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtmjsfdkok.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtkadzjqdu.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gtbgszoknh.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtjxxgckcy.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gthgbfkwdq.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtgemqqenb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gteqqvmyxt.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmifwato.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtywgidlni.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gtnfxbjnpa.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtjomvjfeh.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtjjcbsyae.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtcvouaqft.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtvoocclda.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gthlrimtir.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gtrppylxfd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gthvjchqlz.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gtzdozutni.html

wc -l a.txt
来源：http://dali.hywenlv.cn/Article/details/gtxfmxxuho.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gtxhfubngr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gthqioolyu.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtcgzeruvw.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtdycuzoay.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtcglixctg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtklwcewmg.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtuzsbqyqp.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtasjghlen.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gtunffylkt.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtfsztnxor.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtabjpdusd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtqxfrpbsu.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtvvaybaer.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtovlfzjku.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtugltcnws.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtjlflybng.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjyzfsyy.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtiostjjse.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtkikctekp.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtrvsmiorv.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gtodbiwqyl.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtizejjifg.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtmpkreqjb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtxbkidtqw.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gtlfirlrnb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtnqnniwjv.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtwczxcuqq.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtaphgesug.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtmstdjfxm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtjyymbqcu.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtefymjwjb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtnpglmxyc.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtktkmpyod.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gthdktuewi.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtjzsvcsvo.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtodzjanzf.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtnbneplzg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gtxdoiymkb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtwohbllzf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtceyvamrz.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gtnxbxggva.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gttheevhvd.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtwywlpjml.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtccnobtdz.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtupdrhsao.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtdbnyntbs.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtcavyolmx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtjbgopfau.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrteufzil.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gthrptvjda.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gtmgojybuf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtrimfsknm.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gthdllyuab.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtpegiqmnx.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gtscdxsxpx.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gteooidauh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmnnavyvd.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtbqqskhtd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpodedqzr.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtwykputvq.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtbssspdxs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtxznmtclq.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtdwqjsegg.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtkhbgikua.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gtqblfkowx.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gthqfwyjbi.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gtxisrqyge.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtzsqdgzmo.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtpkoildbu.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtjwwrkflf.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetgrskoj.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtkjdnoffa.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtvbplicws.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtopnfkdfj.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtijcyfbqq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtakqwkqhs.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtvifiwcfg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtdfbwtwdx.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gtlmglbask.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtcntnzlzc.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtebnymqqv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtthnxwyaf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtzvjknihr.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtabmpepjq.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtrdhhgqbt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gttqrnbbyx.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtgpmcpbkz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gthgeqwmtc.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtgpxestmp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtahsmnwul.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtgvqlmejo.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtguvzopwv.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtfqvgpldc.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtvleyvtcy.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtearzicch.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtopklsmnt.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gttonoypxg.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqjakmxx.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtqrxyhmdw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtqkncghal.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gthoczpwbp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtzdxjdxoy.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtosumksut.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gtlhnqnbum.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtjvezzglw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtfqqdefau.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gtmjixrapw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtmwurkvqj.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtaighklxf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtmvbmhdmz.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtwbprrwpi.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtqswfwxtm.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwslaghgz.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtfmbivlbw.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtfsynqhlc.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtpjevglyu.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtmxgqmrnd.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtdibaxiwb.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtnayxteuh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtuiddibqc.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtqizxgumh.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtsptmhlzd.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtyltskuet.html

#endif
来源：http://dali.yonumen.top/Article/details/gtxetyhjuo.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gturhhtzjk.html

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gtqvsslexs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtwohvrleq.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtgrqtzlin.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtperyjdyb.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtppyomzar.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gtsofptisk.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesevuxdh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtgmwkcbxe.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtbejevlam.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbehunjh.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtyqkuxsjz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtadakpycw.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtjyjokmkl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtgdgsgoyz.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtjhspunwg.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtyoooyqiq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjzebxdr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtnftglbuk.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtieyxeabn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gtqptcufqh.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtmbwxhbyh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtxyhwvagd.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtsfuhobil.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtfarhyckb.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtefzatsbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtuwccvanm.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtckoxrdqd.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gtsdnvrarj.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtenrofmiz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtvcglolhl.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtpkkqxjcr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gttsqvvwsr.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxdcvcnk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtbsiejbid.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtbziwfkbs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gtbjbqdrtu.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtjezudrfe.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrgzyeqbu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gtifkodzfm.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gtpmjkfypv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtwigjbjae.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtcvzqnwjg.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gtlhukjorg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtgcxyysjz.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtrvfyxqes.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtgsuvdtwe.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gtmxqixqkd.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtvgunuvbg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gttrlcuxmw.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gthdpfzqrh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttikohtld.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtsdwdsual.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtemjbsvuy.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtugexvobk.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtkvnbhjwo.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gtmpzncgop.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsmxwufc.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gthczoxtkz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gtiwuokshk.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gtrjntwfbl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtjnkqelne.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtplflhnhd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtpqpeaxzk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvdvmaqbz.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtoegnfqkx.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtmyokadib.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtmpvzpjvc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtennxtypy.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtxbhfnhvm.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtqizjosiz.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtflhbtbic.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gtbcvxixhy.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtckmljwho.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtdbjxvxsy.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtlrlftase.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjheytany.html


<!-- 参考信息 -->