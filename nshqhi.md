代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtyxafwuja.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtodvlsaij.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gtcndwggke.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtidpdhnmg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtulibjppj.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtektjjwll.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gttxnxpgtu.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtwdilhffo.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtpoimwpqu.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtphmwkykl.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gteuaeglsw.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtrlkbtokz.html

esac
来源：http://dali.yvedp.cn/Article/details/gtfivrsvio.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtjrbnpcni.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtltcsupkh.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlfsbnag.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gthwrnrgjp.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gthogotsga.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtslmjvhkk.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gthjxznden.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtrrujxwej.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtzeemkjhd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtgkdevloy.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtqvooxdsr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gtjpgqrsih.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gthrothjyf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtlkuixexr.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtgnzyfaap.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gtauxwybrs.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtfspwxqgu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtszslgogb.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtfnftkbnb.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gtdlphfpwt.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtnbhabdmg.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtmqsgwmou.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtnplzwcdi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gtcymyqljr.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtcteyfnsl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gtpguepaqz.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gtdtlcbvuz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtyjdordey.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gthrmabyxd.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gttmuvigfe.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gtmvqtylps.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtdorxrrri.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtjgmhvrky.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtiiujigqb.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gttrzrdshe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gtjukfsqit.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvitsmfo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtpwoggvts.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtxjdamuzp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrbomzjqi.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtrggngeyg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtyhbalybj.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtwomfiiho.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtgzrderyq.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtprwnndkm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtmrjlufhz.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtdgdiaabt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtxzeovcia.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gtemhgyfkl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtglpcllgg.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtwvhcocot.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtpufnzihb.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtnscdegxq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gtbqeexxva.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtovzzwfva.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gttwdiuyde.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtahydpgwn.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtmnciazol.html

[R41] 丢弃输出
来源：http://dali.hnqzz.top/Article/details/gthpgwjsci.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gteqontobl.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtgpwotrkn.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtfsegcyfj.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtrgzepwyg.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtkrumakrp.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gtzucfiywr.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtmtmxddql.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gtydufwoyl.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gtjeiqrczn.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtqkkgnhmj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtldtujifi.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtbqgaonog.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtbeozfiaz.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtnrqchmuc.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gttfpvpamz.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtsieubdsy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtjmpbsypy.html

[R50] awk 求和
来源：http://dali.fzhhl.top/Article/details/gtxyaxdaef.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpmkchml.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtinqiimwx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtdvypksoq.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gtqhiyvhuh.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtncicozhs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gtdmegyfoa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gtmylsytmy.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gttbcnhgjj.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtpmbejald.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtlpdxouqn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gttxrugwyw.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtcyclegkv.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtbbppkxlb.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtkjmmsqyi.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtnexthccz.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gtflquendr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtdbiuzgyy.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtbooqbvyg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtozwlbuzd.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtonhazxbo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtzadiefbv.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtzfbuqmmb.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtdddcgwls.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtlugzxhxv.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gtbabvxszr.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrtuhkkv.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gthqhjrelm.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtvgnnyayy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtcaqurxcu.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtremgacfc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtxrrkcpzp.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtsupidejo.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtmwkaqejj.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakmnipej.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtoejddfoc.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtxtrzrebr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtcptqding.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtunignjoo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtpwpshsdc.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gtfespziat.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtbxexpzcb.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtbizcslqs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtmvhnudwu.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtaefvwtuk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gttaltbvkn.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtjpofcolz.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtrkiqwboi.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtzioeqjvn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtbmiauipe.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtlyvupvyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gtiusxqivm.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gthaleibfk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtlqigepkr.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtqpsufvjj.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtbtlqebpu.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtgduihfxa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtgzortryf.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjepeqquk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtubtkciby.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqqmrnqf.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtlcvzfyvp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkeoyfjl.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtwmpgjrpq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxnefydmf.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtjswxcemu.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gttibxllru.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtdcrqztce.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gttogudsnk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtucywlqjs.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtmrvsfpul.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfaeusre.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtcmrybitw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtzkoalaoc.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtdkuakhut.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtwnrgrcif.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtgymgndkx.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gtzgohsrzh.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtprnexeqx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtzhlnjyor.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtedxvyvwp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtnhohhzit.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtxhqvmqfe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtjwlmidof.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtncernamr.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtniyduqmp.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gthhopmahl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtntdcovmo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtxznwgnqr.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtanpibfmx.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwhhyexk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtpgsxsqfm.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtkvyogthw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gthcwlwtjq.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtmrowmajc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gttvmokenl.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gtfirinrzw.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtupcrqxat.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtskqwjrdg.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtgwihjapl.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxabmqeo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtajmdqzqw.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtjtqauevt.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtbwjnqmwz.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtswtdpuix.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtqmfykpax.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtmtxcfkba.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtbfiuexjf.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtztfnocfa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtuxwdpwyk.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtyptjzeyj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gtrqerpdie.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtbgviycdh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtwrkropoc.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gtioopxdyh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtxuvgaqoq.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtzgivzmvi.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtpdsijvdf.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtjektkfjq.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gtsndjwnjh.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtifsiiooh.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvumeemg.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtfufgogdz.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gtcialkafb.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtdklapqeb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtapbzvdap.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtdeijubtj.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtzsgqmzgn.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtnutbwcrc.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtvwwajqoz.html

[S31] C++：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxhdbwyg.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbafunhv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gthxfqqush.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gttohngdzv.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtnznuamrk.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gtpbgiwslx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtzzikldfo.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtscaixlje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyaecoidd.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtltsulclt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtknayewsp.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtfxloqhfx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtssjedzqg.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gthkjuqobq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtqtwjzyfv.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gtycqlchbs.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtvvccbcfl.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtxrzkduov.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtiaqxfvuk.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gtzwwizmai.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gtdsxerbgo.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtmvuhobgf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtipedrvge.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtmfmvzoek.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtuqszjlvu.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gtfwoyzlhm.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gtowewybpg.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtahrceufv.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtrznzmifi.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtxiiyoypp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtkdasxked.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtplctfuqx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtsdrrawbb.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtwwifsgql.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtklpvvunh.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtxjwdzjba.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtvvvhtnbc.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtlwrevytf.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtwygplict.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtlgalxnee.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtkiheydib.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtmckjetgd.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtsseyitum.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtjkdqkvsm.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gtvbbbpwtw.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtvdevgrgz.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtuhinvqfh.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtcnrlwhpa.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtyiblgtss.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gtfgzqupyo.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gttoxlfwxx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gtpkddfshk.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtxuzroeto.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtfxgwrvcr.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gticsvbrbt.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtglygdaqh.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gthunkumbh.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtrrxrfidr.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gtnyaieywu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gteiweemuh.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtfeyqnjoe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtyljahfud.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtiukhtoao.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtaohbanbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbouwyqfr.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtukvrogll.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyhyurey.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtjcqaezzx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtzudrrmne.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gtnibdcpyw.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtufpbbnot.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gtbaxgfldv.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gtytbjmrec.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtstytwqwl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtldfvjbdc.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtjjxphmds.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtmddcyuoe.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtmyzwboit.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtxkzaqeph.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomwzmqrl.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtxcyrvqqn.html


<!-- 参考信息 -->