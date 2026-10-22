代发 wailian999

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gt2rnulcwex.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gt2nellzjab.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xylfe.cn/Article/details/gt2lltfrvjm.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gt2qtmxfbgu.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gt2acsirdcu.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gt2cedbkzsq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2bjnxubve.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gt2bgxprkbz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gt2ncfexmaj.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gt2tdunmqts.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2pmhrvzta.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gt2gtstecqb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2oncqziig.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2mqfftiod.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gt2ytqezopx.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gt2tvlfyabb.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gt2npmfkwqf.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2xyvangjy.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2umflxkpk.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2dnbhxovn.html

esac
来源：http://dali.0kj1m.cn/Article/details/gt2ryiaxzlg.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2pctuoazx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2jzdewlev.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2uphybtcz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uihimrgo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2opjwbewk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gt2mryznxtf.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2skgczgxv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkyejlfj.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2kigvpbex.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2ycdrhztj.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gt2fnsgwhrl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2ewyxtclg.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gt2ftltexsr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gt2kurepnge.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2pzkojquh.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gt2vlxkjher.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qktdytmd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pontduwg.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gt2yghzcvez.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gt2fevuoqpi.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2zhebotzw.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gt2jfglkcsv.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjiuxnmu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gt2ryxdrlkt.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2zeflfdqk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gt2emuydamv.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gt2dyhydtso.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gt2iwinpuic.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2jbaloypw.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gt2owidqflc.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gt2lmioxsga.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gt2naudwdcw.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gt2ibvzvpln.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vexmrfkp.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2oxhzlrjp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2vzmypbnd.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gt2rgnbprrl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gt2hgczfctf.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gt2shclkbwz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2lhsosrkt.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gt2oamkkqjz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obautuqv.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gt2aycssmhs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gt2pvzkpexp.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwhxzruc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2gabztfrd.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2etamvccb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gt2jxtsktxh.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gt2ihathgxs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrcewnfw.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gt2gauxapdh.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fejecwxu.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2srkcydny.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gt2vcmordhr.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfbfgjld.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmymfhim.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gt2kuzrmcbl.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gt2cnqhaahm.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gt2nkaqnxvg.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmpkrpgl.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gt2mmslzswi.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2xtkldbqc.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gt2pkwyndnf.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2xraeinry.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gt2kqwwldyx.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gt2eolxgwjf.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gt2ertiguul.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gt2cnbgbvsn.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gt2kufmxgjy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2revkrvmh.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gt2lbtspmcj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvhucfti.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gt2fheszvss.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylrbpyyb.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gt2licupnej.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gt2mikaimdw.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gt2yynzmczc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtytwltt.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzmfpdmo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gt2moyeeuba.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gt2mngsfofz.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2togorafm.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gt2mplomgta.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gt2aauvxydm.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gt2npovydel.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2lemhbsza.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gt2anxoxlcr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gt2lahwsiec.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gt2chpxvohl.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gt2opszwiob.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2vzymmftt.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gt2crivzpvw.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2tshcmsab.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gt2lzgzyhea.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2doesrzmm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gt2lijvgwes.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2bqpzhawr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gt2lfmguxol.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gt2uwrjaqmz.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gt2nywffiji.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gt2rsbuldas.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvfwxdqd.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gt2idoxmaix.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gt2vknoyfzt.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2lxmfjuwm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gt2pfotztmf.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gt2fmpouocw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gt2jrlsmmow.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gt2wlgbiwtp.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gt2oamznbam.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gt2ggbtrssl.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gt2dqkwlkvf.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gt2mcfpywsp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2lqfblhsv.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gt2twgzibai.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2esecparq.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gt2eropejnp.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gt2bzezvfzo.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2wqrhfvny.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gt2tqputcqu.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2ezkmaxou.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2gicvqfeq.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gt2nbazgexa.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gt2xhvbgizc.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtdxkpru.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsucizpk.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gt2itghzaja.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhrjhjyt.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gt2gdwqmjqm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2xuljvbyw.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2gwhnuxon.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gt2uqwcugrc.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gt2aynvempe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gt2ighgbetu.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpomvcvi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gt2qkscnuqm.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gt2txavpnvq.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gt2arzchdgv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijsnkmer.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2qdbovecs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2efxiadyq.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gt2lhdonhbr.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhxetcbu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gt2mgqfvzfm.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2cjfolulv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gt2zeglsyky.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2wtejjkxd.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gt2xaujdiit.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gt2asbevklf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gt2czdpzdne.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2fqywuyfk.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gt2rfjpdmrl.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gt2qylzqgdk.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gt2fjlvnkou.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gt2howriezt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gt2vpdpbwga.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2xynwpofw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2uljxmuce.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gt2ftxtwpnn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gt2fdfhguiz.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gt2zaqregnm.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2yvnagoyg.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2klplykho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gt2gafinkak.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2chcjqkky.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2sskytxff.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gt2uxsarocr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2qrtpxmtt.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gt2ugckqblf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gt2zwntfvzz.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2kzfbvpmc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2vyfpqdwq.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gt2cretsgil.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gt2drirvpzp.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gt2pzasyjic.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2todkftku.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2sjetbwnv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gt2ogfcehst.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2gljsffme.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gt2nuqjembn.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gt2ezibsvmt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqpvseb.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gt2faomkfhk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxhgztre.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gt2opycttvf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gt2kgrarxbd.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2kaepqjly.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gt2xbzzayru.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2fohiwjca.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gt2taeqhmnn.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gt2bnncrgbu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjmqfcnw.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2puehnikc.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gt2qvuoznft.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gt2awfgffne.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gt2dupvhiyr.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqrpxkjm.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2ygkjxqha.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gt2kexumelb.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gt2gnepycan.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gt2ekrdduno.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gt2rvtmcdtj.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gt2pricmxgp.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gt2dixyhtbe.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gt2tlkdhmuj.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gt2xbtovcue.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2uclmseof.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2abkyjjct.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2coytmnjh.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2tyjoasxw.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gt2belkdbiy.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2zbwdxidr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gt2amzzxcvo.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gt2cwskbrea.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvwyyepc.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gt2alslttww.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2gosbjqcb.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gt2lekgxaam.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2pioaxgbv.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xstphggq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2pagutwsj.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbtbpkft.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2girxzbpd.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpvndmyv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gt2wmjuolmc.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2vqcrmcus.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2qavqjwsz.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2ojntoiza.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2uoudojlm.html

[S42] C++：继承与虚函数
来源：http://dali.hnqzz.top/Article/details/gt2djewjbte.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gt2bdcjoonx.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gt2wzsoqgjn.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gt2vsdhkjot.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gt2uguutbsv.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzovwaee.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gt2rnidygep.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gt2mxisrben.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gt2dyhnvvrj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gt2ceqilrfa.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2dustzeyw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhumvmew.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixzuyyeo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gt2yfecrpmb.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gt2khwkjetn.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2qglfjbwq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2jaylplib.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gt2nalqrpfr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2vqlwdoqj.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2veyrmxcy.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gt2efsifcun.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gt2szhcvwkd.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gt2nvyfljjc.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qiteiqmf.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gt2fbmmkski.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2ieluskpo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gt2jcuwgxcn.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2vwzrbtyj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2upumhxtr.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gt2jsfzaudy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gt2mbjgjnzs.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gt2ysnnvkyn.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2cyslnbbb.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdhfvosm.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gt2orpufums.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gt2edqukhrv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gt2lwygklee.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gt2ludrtsdl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2bcxiafsy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fozbiugn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjlubcvx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ogghyfqg.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vijvyqqy.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2zorfavit.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gt2grgaullp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2czpvjxkf.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gt2qdciwvik.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gt2gbakbmlw.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gt2vwzcimsn.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2hkfksnxr.html


<!-- 参考信息 -->