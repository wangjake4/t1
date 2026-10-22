代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxzfurc.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gt2lnnwpyqf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2bfinpupe.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gt2lwphbxaw.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gt2qlezwjgl.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2ubafyksi.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2jrajerjy.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2vnvmkwez.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2yournrqm.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2nttsodqc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gt2nqjcbhwd.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gt2cwzibcuc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2apummjkt.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2poczmwie.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2nnholllj.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2mikhyhyv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gt2xhiprtcc.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2oeqkyiax.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gt2ccyoncls.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgzpawrd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gt2pxlehuhs.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gt2snhudiax.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gt2mvxijdsz.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2xvfhavfb.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gt2xfkonutv.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkalzkep.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gt2yfqwnoib.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2sfwjclgv.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gt2eezneako.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhydsioh.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2mrvlqain.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2jpmfzdem.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gt2rxfcnvja.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2gsqumpxi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gt2imhamliy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gt2quvxekmd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gt2llypvxrm.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gt2huwjmqns.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gt2eiluploq.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gt2pflzfton.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2fcnvytzm.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmrtkwkp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gt2qrcquxuw.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2uawycovg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gt2wxssatbt.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gt2hjfjjrfo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gt2kjvvoxid.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gt2sudnphwm.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gt2wvixlmck.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gt2kkswwzxx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gt2gdbunczk.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gt2ckwddznk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2xucnfkie.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwzwjtta.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2tnhzxvdr.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2mmboaiwy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gt2atunudgz.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gt2exswkcxq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gt2zxgtsiil.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2meowrkkf.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gt2kyifgjrz.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gt2tbsuetiv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gt2tjjmuypl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gt2rysqukup.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2uecbdoaf.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gt2kokzigof.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gt2cujdqnzc.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gt2pfofyeua.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2jblgowkl.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gt2njqdfhhc.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gt2sjubekgv.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gt2aqyjzojk.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2emdxwrrh.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gt2gsaanizi.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gt2rmdfnsbu.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2heoxqrmw.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gt2dujeplyv.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2vpzwsged.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gt2jcudbrdc.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gt2vfsqaubz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2zypruwqn.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2dhkyhvol.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2ayjpylwm.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gt2kkoocaiy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gt2kueesevt.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gt2ircliijz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gt2awpfcali.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gt2polzisar.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjhslvpo.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gt2reujsbgt.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2yymrvhwh.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gt2kboqzyzu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gt2rmaeyzdy.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gt2dstvxyxn.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2lqfnogpz.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gt2vilkvgss.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gt2jpjkgqco.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzhsjlrn.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gt2pjuazdtn.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gt2qveqrejv.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gt2mguycerr.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gt2ekpbtsdm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2eteunxtw.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gt2lnybaxgz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gt2sewuvkdz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gt2kjtddysv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gt2glzvuonf.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2ivkupqtg.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gt2aognfcoa.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gt2hrrtfwuk.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gt2xsewphrx.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gt2jhnefcrv.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gt2zbujkkmk.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gt2yjumknok.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gt2zpkxacht.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gt2dfvviouv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2gymwodvl.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gt2bldhafbz.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2unrhfqpm.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gt2rxjidoqd.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2wqbmtdyp.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gt2gksbzvvb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gt2uyhhheqs.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gt2cpwlkjxf.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gt2xmwpqibt.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gt2ijfhhpkn.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gt2pkwyabli.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2xlefpiex.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpfzcccb.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2vdrktkdc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2pyzbdfgq.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gt2qdshehnq.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gt2xtddpxak.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gt2kjvsanzz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gt2csbytcmn.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2xhkyyoic.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2cypfbkes.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gt2tirazdzd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2zewhjbyr.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gt2fukgvonr.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gt2bjkayukp.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gt2vpyezylg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2ihhfympy.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gt2fetoorep.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gt2jnbugpds.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gt2mmjtfbyl.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gt2hcvplltw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ldtdjmfv.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gt2trtpzlma.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2gfzagauo.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2fkiyfhfx.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gt2wihjvuhd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gt2ghlxbzvb.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2lkhwezvg.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gt2ppsrswni.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gt2stpvelqu.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2wnycvncf.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gt2hkipvuxj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gt2hmbtoqpx.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2aaloxdht.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhzonxcz.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktaagorv.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gt2netmqdzo.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2fbdjaoin.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2sqhqlsqj.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzkytxnu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2rcxwqxsm.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gt2zjysyran.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gt2hwmwbyfg.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gt2brreppdt.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2nejttoyr.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2mmkqtvrb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2kkoonglv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gt2pbbfsexz.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2bgwnzcep.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gt2eiwselkl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2wpuoufhq.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2ikebjdrv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gt2vynyjeyk.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2kthrcflm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gt2xxftibxe.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2wyozfrbs.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibcjcdzc.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gt2maxvxakf.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gt2pyaislve.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2byrydzfe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2xmijtmqj.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2cwzejvxb.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gt2rbixmefa.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gt2nicaskzh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2hyibezrm.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gt2swjnqoot.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2sowrjvjq.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlmclzbj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gt2ksgppuuh.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmqbgkup.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybiotlrf.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgyyofbx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gt2mxitgtfb.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gt2nhmzcsns.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktxdcdxl.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2mwhsxcgo.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gt2jdcqaaww.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gt2paakvreh.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gt2sthwdnlo.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2slokxuyp.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2ccagjdxm.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gt2xqdrnzdq.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gt2obkirtnf.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gt2ftkkisjr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gt2mgoluyra.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gt2gbiianvb.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bssfyqfh.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2fhuxrexb.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gt2frxkclah.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2ohbryfvo.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gt2nfucvglw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msoivyko.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gt2soviuyhg.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gt2pkpxlyns.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gt2uliheewz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2wkmlmqqq.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gt2bgpsjzay.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gt2kuxdstve.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gt2wnsdylqp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2tdzkghmy.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gt2iswafkqg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2oxyilnzs.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2jmadphxv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gt2fylrlyrk.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gt2wyurzqas.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gt2qicwnnid.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gt2zuhxeqfd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gt2qnqdkaxp.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gt2fukmjkyb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gt2ltcbvplr.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2alnaulpr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gt2azdnbgzl.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2gmiqfkly.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gt2hdlsnvny.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gt2ybhkujkn.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gt2vzzqcvia.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gt2lveezhmf.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gt2ymiczptz.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2nmjzchvj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2pshzrjkf.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gt2dthurxqp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvxuxoyl.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gt2znpanjiq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gt2zbfohhvi.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjabjknz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gt2vnfxayxz.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2fumldqiw.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2owgsxahy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gt2ibdhjdqh.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gt2qzgdaovc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2lgogmnzt.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2eqdkfesc.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gt2apqbphsr.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gt2doogqasr.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gt2oqhilbwo.html

[S53] C++：移动语义
来源：http://dali.zdqjudy.top/Article/details/gt2whfvfobo.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2qpzsxluo.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gt2huyekori.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2djygngus.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gt2exxnqkhe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gt2udzhoyjk.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtzbzszq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axmppimz.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gt2xpnnhgcf.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2igldgqbb.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gt2vlswfuoe.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gt2olvexdmb.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gt2mnwcafku.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gt2jesrvxtm.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2kuosctja.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gt2keotgaap.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vwynjvzb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2feyztviv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2xflogglq.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2hryvmrcd.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2nwcjwtiy.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gt2xoctgzyi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2ggyuyeqz.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gt2bwbvhgdk.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2qmlcxfxn.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gt2mjbpryjk.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gt2vdxzmcln.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2frwynsld.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gt2txpfezvr.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2ptiypxzc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gt2lkobpcyq.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gt2zugaodjm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gt2popkbcbb.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gt2kkxnbmwd.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofulutoo.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gt2yjrqbvkc.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gt2gerzpqlx.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gt2izdsesni.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gt2ojahkwqv.html


<!-- 参考信息 -->