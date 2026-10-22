代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtmhwqcoiw.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gttdczgfoa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtizddppqz.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnilwukbq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtlakbuhhe.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gtpwaajeug.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gthkhfdlhh.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtxeqkofsi.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gtkhfinvgu.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gttbhtrxwy.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gtdfspafnx.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtdzojzfzg.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtqrmdbodd.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gtngexqeui.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gtbvnlvulj.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtkqmpqkfb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtkplarlnw.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtveqsurxf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtalgtovuk.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtmgozzofn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtncwbnsea.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtqrevitww.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gtfajvvjid.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gtbytnaynl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtlduvzeou.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gtkdewrbyi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtmwuepssk.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtlxhyzrbb.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtwsbtprqt.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtkgaizwac.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtqsnofcjj.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtedtozipm.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gtdyjyhios.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtwbxudtby.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gtgqxomyrn.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtldlomfya.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtasgswkxy.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtpryruahr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtagxbcioz.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtnjhkzfxk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtypgwklxx.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gteefjxlgu.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtdcegvckk.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtokueiyuh.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtegaggysu.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtwtbgegjg.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtlzjtezls.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtppiqqial.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtrrddnfvr.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtsmkqebgf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gtmoelvumt.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtcothldrv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtfhmackcp.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gtyuoihsqv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtiluwtnds.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtybarwwwa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gtjtwxjwdj.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtqwygzmne.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtnurckmbm.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtolutrbpx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtsdspwqlx.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtsynauhhq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtyxvupfoe.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtjdczuljy.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gtqisswykc.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gtsbbrpcfu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gteayoafen.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtpmrohfbp.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gtjmsndsay.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gtflwcjuhu.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtxxhjikwl.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtgiutbymz.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtpulfbwre.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtihztnbaz.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtdrpjzudw.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtsrkwafpc.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gtnpcxlixc.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtrskgpeum.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtusqinflu.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gtolqzmyuc.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gtfmxjjusg.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtlkgwljno.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gtzblfkqbc.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtjhwpboju.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gthzulozqh.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkksolyya.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtblkiqymi.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtrlterowh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtkrfkycwn.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtflgzkfmx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtsskmkedd.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtcangkyok.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtlxdlrtih.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtpokmqfjw.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtakygbrpg.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtmlwotgtc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gttswkwwvv.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtbhwnztpr.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpgmwoyv.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtggeskqpy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtcbopjbtn.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gttscpaldp.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gtmnfqeziq.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtsefweiuj.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtahqtyjaq.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtfkcnmckz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtneigvres.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtqtaqbhgr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtfongznwf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtgbwqjvyi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gthqqstlhz.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtjtoqhbfk.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtloupelvd.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnmhegor.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtcnpdjbjs.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gthvftttvr.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gtcngzuiat.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtbhtwxhiz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gtnqufdrig.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gtbyofetve.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtjqpgntkc.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtbybinytn.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtlimxraai.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtaheytdpm.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gtiufxypll.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtvpzykenc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtbujylbjf.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtgwmfuivq.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtacpqemns.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtwowigqar.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtaicyyalw.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtujbwmajh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtgvctdqxk.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtaaojysnb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtmadelpgq.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtummueqri.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtwrgtxwwb.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtydlrwkzx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtznibhmzp.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtzmgqbaza.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gteknwntcf.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtgayefrwr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtrtkbrwhs.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyeztinv.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzymswdof.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtsgqvowkg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gtqiuwmjsi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtjirbyvvx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtunvlxrwd.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtblwfleud.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtqssspkom.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuxlywpgk.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtckpdrmvm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtokyfggdx.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtuhxpaemc.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gthnhfeqfz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gttlcsdfwt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtcfdzyqtt.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gtrwaxpabd.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtwdqhilzp.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gtqbjknvpk.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtofqzgurd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtscgksgdl.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtzlkpmtlp.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtrtjnllnf.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtcbronebl.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtrfnqsoae.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtzyxwuttd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gthkzpyjrt.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtveywidbv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtizijdnui.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtcjmykwyd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtqwmldawr.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtjhmlbfcv.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gthmrjkqqm.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtmdvbjfey.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtztylmdkg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtpjcpmxuo.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtleyoxgtx.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtwgrdilts.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtlymwslls.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtoflyfisv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gteywgqdtd.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtczbwotoz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtrfdodukq.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtjckrwzlu.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtdgixdyyc.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtjajnlfob.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtttnkudmx.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtmrxrufol.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gtczzctccz.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtakhdqzgj.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtowbplisz.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtzaibcsem.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtpamnnybo.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtsjoypndn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtybgrfytd.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtfvfcrlxb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrzgxawx.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtudctyfaz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtppxmhjln.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtagxssren.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtmdbdbbtw.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtjdfszwws.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gtwwpijnvq.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtyzxcdaud.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtxdzqvvjv.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtmedcppjl.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtnkmjtqhm.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtybovegzh.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtnzyuaufc.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gthzhgbtqk.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtdcrnfkra.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtevmbxszg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gttfzitxhc.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtxbdegegy.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtyissiuzd.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtbgrvlled.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gtzyivdtmw.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtjsmtvbio.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtbxozujjf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtdggsxecl.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtuxwjprpw.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxubgfuam.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtynuycltg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtbvpewgic.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtlzbzlmlb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.svipenyu.cn/Article/details/gtqyancpkx.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtngdeyzju.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtyszabgmp.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gtakojlucu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtrpiaxahp.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gthplfluet.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtetpkeyfn.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtmkmeoios.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtfagcjyvv.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gttmmdjixu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtizlsjpra.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuevvepk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gthrvnvuax.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gttzumwpoy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtvpdjwflz.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtnkxofiso.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtaefhiofl.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gtdsqaebag.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtiwmufpzk.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtljxcswoq.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqozueiax.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtbcckyejn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtlwydnaxu.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtvgkqtruk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtxhydsbkh.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtiqkqthdp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtupgwoaxu.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtmzarptuf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtyypggefn.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gtmqnaryfi.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppxqfpmz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtpofgciyy.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtywduxrvx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtxczxqigm.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtldbqsomy.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gthtwtmdpo.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gtkyoeygir.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gtgvonzume.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtnevfiqaw.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfhstkft.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtdjdtvmhp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gthqatzkpd.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtvbftqyhj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtamawdmzu.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtchkodrdh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtwujbwakl.html

[S57] C++：编译期常量
来源：http://dali.ydzc1.top/Article/details/gtqipxnpgv.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtnjonxfmg.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gttduguejl.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzmjegnw.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtybgzhsln.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtfbdhnake.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtmmksnrls.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gthzqnegce.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfzmnsoia.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtxumqygqy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gteebojrmo.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtpbmtktdv.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtuvetshet.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtvdjrjwtq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtiglixlmr.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtakfqbpho.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtilfzzrco.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gtupmtuzqo.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gthxvdhlhj.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gtdtxwbysi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtzbcqxsol.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtwvxqfeiz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtlpumfhwk.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtepastqqi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtljdunjog.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtbqejtxvk.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtbghosnab.html


<!-- 参考信息 -->