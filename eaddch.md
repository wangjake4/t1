代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gterzotiip.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtpgbnoacu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gtvjfmsnua.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtksgvyyef.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxfgrgvw.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtxxyocjqz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmjyrkff.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtxfvzewkn.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtmumbtuyd.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtssaljkav.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtegabordn.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtmocfammu.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtjlcyuwek.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtbsfoqlbl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtwjfacrbt.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtmdmgviza.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtqnysdzex.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gtucjlfxaa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtvrzubuey.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtmohnknzk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtinbmnzqd.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gtxjkrktww.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtxcnixqwy.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtwnosvqmo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtxsopabpb.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gtnauhsjzq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtfafrcmuv.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpbiaymc.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtjwwogppk.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtlxxabidt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtvxwruwpl.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtkixhddeo.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtqtprwuzf.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtwpjffqxm.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtjwchphek.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtuxkebmco.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gtfwxpwaby.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtbzgckjwk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtozhtptqx.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtpvohivex.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gtpxmanayc.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtluieybvi.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gthxvihjvw.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtrsohjcsx.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtfiqnoqah.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gtrnlbavca.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gtwcjgupbr.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtskzggvey.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gtpqbnxgrt.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlktzvfd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gthlxmhjmw.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gttfblstdn.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtejvxhztm.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtihtoasai.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqhegyrzm.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtbzagibdi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gttcqttecx.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtkeykcaic.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtqidpwxpy.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gtqaevgeto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gtdxlzqide.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtcnfnwjoi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gthfhxenwg.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtyaatjvyu.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtiiyabwyc.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtmyksyoca.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gtkfbxngxp.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtdfueednw.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtgtelckzk.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtlrqhuviq.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtukmdoszo.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtaijltfsj.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtwzogqjok.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtkvniejea.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtfiehkkkt.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtzqfmrozb.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtqvazxkgc.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtewrodxld.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtssmghtev.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtnjadwbma.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtxycfrahq.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gtitneeyyz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtvvlsmlgu.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtcruxuwdk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtnevovqjd.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtlguvctnz.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtyaewanzk.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtmlbgokcm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtbmhtunuv.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gteyewitdd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtrlpeacue.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gtjpsgpqks.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtxmlxuswk.html

[R52] 统计行数
来源：http://dali.dashuyun.cn/Article/details/gtssfopylh.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gtmtqguwyd.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsadsbvm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtfipwajwa.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gtlxerfgdr.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gthaivsxyx.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtaljmrpko.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtpjmpfykx.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtfspefmwd.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtpbcohhgk.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtwbdjbuvh.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtidrcrhgo.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtkbretbje.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gtxaqenrvf.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gteznykhqc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gtetygciej.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalyfkauv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtwcixhctz.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtqgqcgwmy.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gtmprsmauh.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtsthfnklq.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gtctzocyud.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gtcbwsswkd.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtnjmxfszv.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvugqexg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtufacetnf.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gtznvqlsei.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtobnxxocz.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gttvjvlhuv.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtmxrhnoiu.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtwbtavwzh.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtcchcptmz.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaapthptz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xylfe.cn/Article/details/gtqelmhurq.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtpxznhehc.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gttdutjxjg.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtbzjhwutc.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtilyfsodm.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtljzrdztn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtqlrslwms.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtqotbrygo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtrrzchymf.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtwvwlwrct.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtyhfumzjg.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtspasmghb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gtbvltvbsc.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtevqigpla.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gtmyplivno.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtvugfaqkq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtjcgmlbho.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gthngufwiu.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtwzyuhkuo.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtyzllulsb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtvwamrikh.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtnarzmqoh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtoxpsyyuw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gtoxlurish.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtpqyrgbdd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthbrkbgos.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtuczyvmpm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttmokukvv.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtzzcxakkb.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtwtnvnjmy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtvyppxhqt.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gtozhagfqj.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtcgbuoupj.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtzdcsciiq.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtgvalcvrv.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtdbenipgx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtxfkfrhaj.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtaffoplob.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtekkngbtp.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgahkqnhx.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtcgwdhmya.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gtisormscz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkitsfnr.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtqkbmuayx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtzgwynhoy.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtjxxpjykt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gtmdepvxni.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtyqgrtvgg.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gttkwiztpk.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtjyeutkgw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gtqudimzre.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtcffksjiw.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gttbnklkej.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtjrezcwil.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtrmtyzlyk.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtzhcdjyet.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtpojztvii.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtyrlqgszo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtmxtiaplv.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtijubkbrp.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtutysfivw.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtjuvjgvxq.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gtlopreumt.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtxethdrlc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxalnmikn.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtyknlppoo.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtwlhjhdze.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gtlkhthbpv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtxdhajwnu.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtgfswbepw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtkwxnrgms.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtuntwmmjl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gteiwhwsfa.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtukebbokh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtwhlcmnfr.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtgwagrjzk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtowukemcn.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovhpfbtj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtewhfcjzz.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtffdoypap.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtxajnndmd.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtoyxsktca.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtzjnbpstd.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gtfwwiftrj.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtkebygpii.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gtphzvohth.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gthzrzzskw.html

[S29] C：变参函数
来源：http://dali.tanke756.top/Article/details/gtmlkvozgk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtejmkcryx.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtcediiaip.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gtuuedckgo.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtjqeglqju.html

#endif
来源：http://dali.316326.xyz/Article/details/gtuzybtzyc.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtrddjbxwl.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtllqvuarg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtzsgzkhgn.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtjicogdwf.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtokdzwjrj.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtlsbjssln.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gthgfdiqcs.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gtwbjvvrjv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugqzokty.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gtkxesilaw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtyefptfdc.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutkkrwsa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtpgrifvkq.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtbmjwcjxf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtgbjkakyd.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gthmmdabmw.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtntewgfhx.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtcxutbluu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtoitbmoqk.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtqamddjuo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtixixfyii.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtjbhiatin.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtamoiepyu.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtlszbkcgj.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuodquutk.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtckkdeusz.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gtatuzousb.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtpjejafuf.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtbreaskvy.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtzgbwrnkg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyntiodo.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gtciusdovy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnmomyzw.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gtxdcwagbq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynijmzfh.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtbwfvxdvm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtyubgmlgm.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnixvzjdm.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gttiopsjkq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtsbtxvzhb.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtxsnsoffg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtfdrnrfct.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtjlfofvnq.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtiewdvuie.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gtqjofrdqy.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtinuepirc.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtkyvqemrl.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtbmbcjfku.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtyumvggpe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtibwemrhy.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gtmnwloobz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gttgwdzptn.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtkjlscvgn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gtcnklmfhh.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtmhsfehjk.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gtnoopjkyh.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtdggetogl.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtyvuxomdg.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtcucevfom.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtbdbzjlrm.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliphsxmt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtfbzxzarc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuhpzmsoy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtmhprxwvw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdctdlrtk.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gturiikmac.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtzmkfkyev.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxnqryrig.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtfmtfqqno.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtjiqacjbg.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtxchwhssl.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gtsppcngpo.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gticbvdgam.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtfovnjcfh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtrzjcfwcd.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gteccdorbi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtnponejqp.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtnhcosudo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gthcjsnlpf.html

[T08] Kotlin：数据类
来源：http://dali.iojbl.cn/Article/details/gtxukfwnvg.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtsdxrbrxd.html


<!-- 参考信息 -->