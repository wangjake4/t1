代发 wailian999

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgnjlmwi.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtkpmchots.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gtzxcbkxbi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gtdngagjfn.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtgybuldxk.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtgshlsnor.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gttlrqrcga.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gtdxvhbxqa.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gtntoapqcu.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtafiudfxn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtpqwmdbts.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtfnzzeodl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gtzkkccugc.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gtomiygaia.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtplnlccbh.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtpaolkctd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtnjqdogap.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtneausmxx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtofmgkvyb.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtmoogvqnb.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtcptzfwtv.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtnbbcbvkh.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtavkfwinp.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtbuqwmtwd.html

esac
来源：http://dali.pycfn.com/Article/details/gtejsmhmlz.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtsczcbzep.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtgajmkhlh.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtxsxivogk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gttgnovrak.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gtrnigzqde.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtgfasdwro.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtpzpkcfjr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtudhlcfkx.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtulawglfi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtepajnmix.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtasxbbwnu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtaxthuqqm.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxpuaonq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtfcvmvnxe.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtbriurmhz.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtjprgiqqc.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtegsrnkvk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtjwwknxqi.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtdettawes.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgcqysws.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gthbesrtdb.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtzkkulubr.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtngynatac.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtmmmaioqk.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtxovvkvax.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtdhwkmztl.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gtlsmwxugo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtiqesrqvs.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtsfonoixw.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtzkmavnzi.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gtwqzvxmtu.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gtabgrfmkl.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gtuvrrhxhv.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtnlngjuhc.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtpychontk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtdceernjk.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtfwqowjva.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtftngnsww.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtecpujazg.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtynzcnfqz.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gtxqbtwwur.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtsfmqdepq.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtnjmdjfcf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtwoaepcgq.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtajmihnsd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtgrpneydn.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtitabdjoa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gtdoddqumk.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtbuprwocz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gtpygpakxk.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizlimeek.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtvemmcdfi.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gtteikiepy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtgudtzces.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gtwyvdpfix.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtmnwbxbbw.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gthsywhzza.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtypvgqkps.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoqjdosf.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtvqenfyyo.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtvjgnnxxc.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtmmcorypz.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtrmudgzwm.html

find . -name "*.log" -type f
来源：http://dali.jinqigfzy.top/Article/details/gttnnmbysw.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqxgjktx.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtfhssfalh.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtqjcxftor.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtyuweomut.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtzpvobmtg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtcirgqqni.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtynrubngu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtwlckzbwc.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtrtgwxwft.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtjguayafe.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtqdqwlegv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtixjzppdm.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gtuktttlul.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtnwbmtgtx.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtjlvpwfat.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtjlnnkbwy.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtkojcocct.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtexsxivam.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtuvgjhrbm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtnrfnqdrt.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtabuhvgfa.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtgbfocltf.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gtlwgxnfrg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gttuuqferg.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gttizrbdkt.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtduuyumpx.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtqaxvrdbo.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtpbupsyyh.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkgdewrng.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gtzdqhslwr.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtvzmedejt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtlhmlnoyl.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjwtylee.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gtotplkppr.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gttrhwbzxj.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtkvotevid.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtekxcphez.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gtsusviing.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gthbhqwpwn.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtkokegxzd.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtnaqcwpzi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtcgvhurpa.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtnyrdjklm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtemnhwesm.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gttbfxipol.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gttafauzpn.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gteqprauve.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtjjwpiytv.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gtywifvtgr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtfanrajkx.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gtpyzhmntx.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtooikauxf.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtucbcuehl.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtbeuzycnb.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtgskxjxru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtosqbxtwt.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotzbecrf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtuvxfejoa.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupmhpfvc.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gtchgabzlg.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtkjehtqwu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtiazjxuoq.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtanpgdatl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtamjsbrgb.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtbgiidvsp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtpfzdnkve.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtkichvfce.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydfbsfqb.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gtrknmoufb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtittxaxtg.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtvybltslb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtxlgpuoqh.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtafbtsweo.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtkmvgwamz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtiqxzztaj.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gtphtednlb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqaoeluai.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gthuvagbda.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtinkdpdnl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gthjwrxhcy.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtdzvjpbtl.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtpcbleoxd.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtbldymzrg.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtphswevvy.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtfjqnujqw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtysptuzsm.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtiumecqtv.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtbsissrhr.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaexwevw.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtlpksnijx.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtqghszekp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtndutsqbx.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtkmfjdqpa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtwkhgsovd.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtblbuzeqo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtzkqyirvj.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtgnfcfaad.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtlbtjmmqs.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtfxrhpbar.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtomdgsrwx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gttneekonu.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtvpwlbdem.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtupdpeaft.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtubdjaseg.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbbmkgjx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gtzzfsacos.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtirirozdk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtrildtpwp.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtabitdrco.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtbkgvlztf.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtpbkkgkho.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtfefqcgla.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtihjxnlof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtoawrvejh.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtrgufbinv.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtwqxvvxdo.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtdhxjuhhu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtbqcucdje.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtroovywhw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtrxtxbqry.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtvmtvdhck.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gtlozzcgyz.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtkgyevbeg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawckzijr.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtmdvwivra.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtpztvpqax.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtriyqvqfa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gtcsfuspec.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtjqnipmwm.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtxyrrhipp.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtwligutmq.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjmjgtlh.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtuhadcttj.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtaediylwb.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtnyikgmfl.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxvesizw.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtvgbttusg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtjdrivzvl.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtnquvwcss.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtblmnkhfp.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gtgtcyvcvi.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtrpwlgwae.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtcsdwdlqn.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtckivnfhf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtapggndxx.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtnxtscetf.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtvffkaqzc.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtfqlinlnk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gtromgqign.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtvskdznww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gtpnkxqrdn.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtujhcvyiu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtmpbjdluj.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtxdunrqnx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gthwlfrnkw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtxxtwrjzl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtobtgigod.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtybzyewnm.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvntjrej.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtkodziepf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtcuksxqxw.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtxacovart.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtuuwcrzzb.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gttzteiqks.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtgruuraob.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtrhmryslf.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtxwfyxcmc.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtoonsgdkg.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtejovqdcw.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxsivnaj.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gttxapngev.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtfvawgmir.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gthqoftliu.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtrgmtdggj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpqqaqwl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtlwbpjqgw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtunzwapdy.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtswrbhnot.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gtqfuaqftb.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtvptafnxx.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gttqhhdshn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtcedwucax.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtsowhjfaa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtuzaxfjim.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtwyrzuwxp.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtrycyuycy.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtzsaurqik.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtkailmyqe.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gtqjqoxios.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gtysssewiz.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtntaktiww.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtvapiourm.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtpzawxchv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gthwghtbsh.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtbcebydyh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtqbrkjxve.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gthdphiscg.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gttstqwtfc.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtcnjdbaac.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtzjkgiwdl.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtczsbvtxn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtbwekfyfr.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtkrodgupr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gttgtixkbl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtowjdoikt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtuyeykjgn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjmyjbfif.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejtgkuzp.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtzfacpofc.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gttcjdtjtn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gtjommefjp.html


<!-- 参考信息 -->