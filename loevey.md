代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtkkndlsny.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtcmezzmjl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtzvusrpyr.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtkkxtctis.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtcdxibsbb.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtimsynfbk.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gtqarujtfv.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtevstpown.html

esac
来源：http://dali.jianghu66.top/Article/details/gtalghbcbp.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtbufoyyly.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtybirlybc.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtyofohzji.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtfkxyixuk.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gtonblivgi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gttfrbscpm.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqljhrtup.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtosjjrqqh.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtzdycbkba.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtgvegviyp.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtwvprctve.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtyorqcmlx.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gtqnzgukak.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gtycyfvibh.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtftzeehlv.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtixudawjb.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtxhxkcczs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gtchhhycwz.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gthulunome.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gtauvozuao.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtzhcefw.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtenaktjln.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtbydnsfkl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gttohqyixx.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtozdxwcsp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtozvthlpp.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gttzshlmxy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtohkbzocc.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtvcwbzngu.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtruxcrvco.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gtqsbqlgkh.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtdridevel.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtgbzecdft.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtsriusbkf.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtybndfbkf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtjfgzjnsj.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinzawgzk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeicerpe.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtuyuutgwj.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtwqwtrrvs.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gttmewxawo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtrcnalokk.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gthxjgdwue.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtfcijjdmq.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtpammdabf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtzbpbvufy.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtemciqtdw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtilkhpdxg.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtihfpsgen.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtlvzsjoag.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtrgrhtolw.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtvzpektey.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtpsmzhexb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtcbttncmt.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gthjhmqfjy.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gthzwlypub.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtlcbspeur.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gtaefqevem.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngrzmuim.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtglmsymsr.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtsxvudlao.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtdrjmgaej.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtczsjbgav.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gthgnnspoz.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gtixttdawp.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtugciazkj.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gtztleqqcd.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtsyukwuoz.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gteitusurz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtbyyzqiyd.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtczhdtgef.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtfhopzifp.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtukvdxmpz.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtreoiogdr.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtahjbjiyi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtjlwnzwsl.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gtoxsndkai.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtwacdcfyp.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gtxbsfeexs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gtjhiozcxu.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gthnwbulwc.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtekhvftex.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtwoveeayo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheqnvbmq.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gticzvvanv.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtttzatbis.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtjwprleui.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gtainoqrsj.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtkowvkgie.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtcdtzgqje.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtprgatckt.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gthrfrzdcj.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtviildnqo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtsixorvvh.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtiwcitnbo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtjmkktjih.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtoeevtqkf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gtnekmxebf.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtqdntfire.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtpgtrnfnp.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gteovraeqn.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtnxgbebqt.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtvrwlxxfn.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtumxrzfle.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtrdubgwvs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtazbjuqex.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gtoaqkdwmc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gtipztinzv.html

[R66] 定时任务
来源：http://dali.daria6918.cn/Article/details/gtskmwrdaj.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gthzsihdtf.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtbusogfyn.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtpcrsgiqw.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtnsbdvrul.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtbcfzesog.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtgtrowimi.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtbrypgrzj.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtntygetjy.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtptsrnuks.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtmrocrhbb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtnfawmzwe.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gtnjwuoerj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtrlvjwsfl.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gtdtoriida.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtmgciyyqj.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gtsiwsfaso.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gthshnntbz.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtvbjtkcsa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gttcbnctaq.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtnadicubr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtzcytzmrk.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtvyzudwhm.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtloaoqjqd.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtaitoeonb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtqtocbspe.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtmuibbhju.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gtcpmjaqgh.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtakrnmrhy.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gtruujlwou.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvjabrdwe.html

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtvrfcdhtd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyxbxfjwu.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtfkuwdxdb.html

#include <stdio.h>
来源：http://dali.feifeiyinyue.top/Article/details/gtlaipyqdy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtlmadjahx.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gthmjzobnk.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtszjoktpk.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gticxtrxjf.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gtygbxruhf.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtxbwhgdpw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtxcavakkq.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtphjskevb.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gtgioanlly.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtymxfevlk.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gtmjrnoncr.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtkbqumjky.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtuqdyvkwg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtzeydznqm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtrzjfolpo.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlssxtnb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gtfcvscqbq.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtqyhlicit.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gthjfczdmz.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gthgxisyfl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtvgvmkumj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtneguiroh.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtpyvhexsc.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtcgkrupin.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtdpvkfbln.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtuxzyedef.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtbrnntbtg.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtxgrwwrsh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtwodwgktx.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtezpsmnsu.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtphohjlkc.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gtpvkprqlc.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtdwscxwqe.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtsfigralm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtmkawxtss.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtfvyvmxqq.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtnugnyymd.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtltpwljtb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtfgphvwdk.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gttnfqrugv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtylzhmgkr.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtcvvulnhn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gtnjdewcez.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtfmmyznqp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gtyaguccge.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtgpnrnsqk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtwomactxv.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtfninhxct.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtugbmljyu.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtnzjzoxuj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtuzopspzh.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gtutswtlhc.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtyrkwjpnm.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtfpkryeyi.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtsoowaojf.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtwouhmuds.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtvhnwsiww.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gthxhojaol.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtmgyzcsfd.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtjkkxyzrm.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtfxmadhdl.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulouhrvb.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtxxiecvhy.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtdtrstaae.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtfrwjgswv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gteqexnwmo.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtdqogorsi.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gtgkhpbyle.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gtxljxlsri.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gtoilgicxu.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtrihesfys.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaedwcapi.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gtzvmzlpyv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtvkgsdcqo.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtoifhvjxq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtaiyvjlmw.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gttewpppcz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtfcbejoey.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtfestrxjg.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtrqboauul.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtxbsfihpx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gterksttgl.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtrkfdleky.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtdyptjcoe.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtrfboywsu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gtotdrjbqj.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gtfsdwpiis.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtkouqrxvo.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtpqhqczgv.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtrveldzfk.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gtyjwqakit.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtxsjovelp.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtumjyqthu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtsgbkfrek.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtfmnmxyuq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtjdsynhdo.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtuukgbtmd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtxmjomlyk.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gttenywgqm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gtnxeqazzn.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtveahvgsx.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtrdvjnzlz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtqiarvejr.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtdusowsee.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtdhdhdwuf.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtqzejnhws.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtiaaxlkne.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtodpjstvc.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gttusmjtlb.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gttipfkfsw.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtjedtvflo.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtywsnedvf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtwkrsasla.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtegkxxzch.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gtdgmvrtmx.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtttwyjpwg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtphecxdma.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtwwhvuyfi.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtcuqakksu.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtgdunjpek.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtjozybmad.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtjljmmgoj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gtervtufic.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosejqghk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtzkowzafw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtizxhrguh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtvpyrxqdl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdttmalzp.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtrltowlst.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtyerjmxga.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtwjovnvyu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtoaeujjfp.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtjwxgzttp.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtmpvuvnoy.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtlmilbsbc.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gtoztshmpv.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtznksyvil.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtgskgtohb.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaczjziv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkecovvoe.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gthzhoohlu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtvbwmjyia.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gtwexnssev.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gterrhdxsu.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtglqzdzfc.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gtxhjrkpwt.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gtssgpoukr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtmiptyfal.html


<!-- 参考信息 -->