代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eidijxqt.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gt2oedqrbis.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2znlustxt.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shkmfwrd.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gt2wamsflmv.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gt2vuezvtyq.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gt2xrijings.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2evdmwwuf.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gt2fvsyrofu.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gt2gyuitkgt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2htrghbyf.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2mtstqcgk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztjxoauy.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gt2ccugzmfi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gt2kahqpocr.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzeumdzp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2njdquwdm.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gt2eiagjfoj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2salajoix.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gt2rednlnnh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gt2fimrsnjr.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2lkwoqkts.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gt2kbatawwa.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2vrqbshjk.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gt2qudolzbx.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gt2ilxbnljz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dashuyun.cn/Article/details/gt2xnqzxlde.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2pxhkcxrp.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gt2xtflgheh.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2mqjgzaqi.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2frrezivt.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gt2xzkclhng.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2astrycfx.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2thkhulvc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2uycguqtl.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2towoscjo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gt2ccsacsmp.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gt2wyameqgd.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gt2qzgoiofr.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gt2jgtwqbil.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gt2doynaoxw.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gt2hliunssm.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gt2sskpgpqj.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qxgorwlj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btdhlans.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlbbbfkv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvpxdpob.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gt2eybbrtca.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gt2agcstypg.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gt2nfbblkkm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2utakfjcd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gt2tsmddqns.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gt2iwewpfdt.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gt2yslwtxfv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gt2pnwbgtwf.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gt2ujbierng.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gt2fenoqkbf.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gt2qdziftcy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gt2larsdlzs.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gt2qgosoewi.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2gmcrciua.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gt2agpnvzsx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2scypfspw.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gt2fihcqgpy.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gt2wepkzjcz.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2dxzjgbpc.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gt2olsfgkss.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gt2bgezspve.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2bkevirxi.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gt2eypujulb.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqyemeiw.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gt2hdvixuae.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gt2ozqlnsic.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2jradeqmh.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gt2edgrvmdg.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2ogeejuql.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gt2zgcnqotj.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gt2vtyprnea.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gt2ssbwanfk.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gt2vzvfresv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2wcygishx.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2cynhwxai.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2rxpsrfho.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gt2jpvftxfg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gt2xejlizcm.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gt2jddbuetv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2gqupjess.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gt2cnhrieqa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2zptvxpgh.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gt2lhllttqc.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gt2gcexdqbx.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gt2hvnornuh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gt2khhmkrii.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpswdvao.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gt2vhslftmy.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gt2xncfywxo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gt2zchoigii.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gt2ilhxlvbn.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2pzpwynys.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gt2avylabph.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlzgcgvu.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gt2onlphtcw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gt2hebxzzov.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2dgxpogfi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2frjguzmh.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2qznwmucu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gt2yoexqizn.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gt2ziykzoxp.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gt2cpndmzce.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gt2hyuoyzob.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gt2jwwetnif.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gt2epfdoooj.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gt2zkdrwazn.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gt2wjjgdpcj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gt2xgykqxza.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gt2ruxzntxg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gt2hbtnvjpr.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gt2dpvqkmnu.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gt2jamlesvw.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gt2kbmdjxsc.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gt2mfrntlhy.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gt2qcjititg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2tzxwpmsc.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gt2jptjatfr.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gt2cbbzvwki.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gt2kclhcmtc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgglesc.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2lrtrbgme.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gt2ppplzjmu.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gt2kpdigqqd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2xhcofcmp.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gt2wtcngoek.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gt2qbmzcjjj.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdlwttnp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2jwizbxnh.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gt2vibmiwle.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivwmnvxv.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gt2qnhwcomd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwixqcig.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swrhzgdd.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksqzbpqf.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gt2xylmrasc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gt2rmmewbtt.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gt2wswkjvqg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gt2vlspvwuz.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gt2rnegomxh.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbfyikej.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2txnjjzgm.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2riblpbzb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ruzpqmni.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2bxnllomm.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gt2dalzafqz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gt2hoquzdul.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2umufffcc.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gt2okaoxqxk.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gt2mnhdyybu.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gt2kbdevefv.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2spekgeww.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gt2rylelkyh.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jiandlbw.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gt2qfkdpczy.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2vtgwsyyn.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttsyuqqd.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyczbfse.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gt2rckafjgz.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywrxttrp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gt2vlicjifc.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gt2oqdvqjwz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gt2sephormw.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gt2qdmdcfhc.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2gtcmgmaf.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2hrhjliwz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2fkfgyvba.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2cmugxtzv.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmxiyeis.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gt2orcfuhdu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2ajfiswbg.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gt2hpovpobm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gt2bockroef.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gt2clcncumo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gt2frhutrfp.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2abpsiecw.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofytmwff.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gt2waiebbvs.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2lbsrzsge.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2sqgbjust.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gt2xptibmtb.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2iboohucn.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltqtsxxn.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gt2rsaxyfgd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2ojvnltij.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpmbzcil.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2qumczwei.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gt2ejpnezdg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gt2xowpzzrb.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gt2vygjecnd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gt2ipabfvpe.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gt2sjlpsqmk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iepsradp.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvrbyoya.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gt2aqfumnfs.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vblexbuc.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2pizmtjoq.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gt2woymdonk.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gt2yauuffkn.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gt2obiyxqps.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2aedjsszd.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gt2uoyehmha.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gt2lreodkvn.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gt2zpgualdh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gt2mkbzanwi.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsplgtjv.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gt2pwtyzsrb.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gt2hptmnpyq.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gt2lqcpxuqq.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2whxnktmz.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gt2wkvkqbvz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zvjtuawk.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2udxngyzh.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2vdfgvwrq.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wczxeeph.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gt2drmgoqms.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2ymogfiww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gt2rprbjhcs.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkghdens.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2tcxibzuh.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2kfjdxxib.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2zhzlapft.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpqhcurt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gt2sxpubbgx.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gt2ixrwrnyk.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gt2pyqslprj.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2cexeqssw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gt2bzurugvj.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2qsdprbtv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gt2iiwjmbzl.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2lthziizk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gt2pwqbpzan.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2gdzrzwdd.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gt2vvbzmuhp.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gt2beqxgsxp.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gt2pjqmwdck.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gt2ddonnxtl.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kydmpmhb.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gt2wdaqdurz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gt2acxxibaf.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gt2tplfsdhn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gt2ekvcrhsl.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gt2cmmfcymz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2gwotwqna.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2uswajmkc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gt2gzmmlqsu.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2ipinujrw.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2rllpzcfg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gt2fcghxumg.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gt2oqpzoelm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2bqsqnviz.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gt2jldnenib.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gt2kmcjrvby.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2bogygpvl.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gt2lmxouzrx.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gt2qwsqntzz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gt2oisfimhu.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gt2khofmreh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbvafxjr.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjdidhff.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2solczqjl.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gt2vtqvwbde.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gt2gesgieqc.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gt2ncchoyqr.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2ktepeuky.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gt2okyyefoj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gt2mzdhlkcj.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gt2maslthob.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gt2jgeaticg.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2qpwdpvha.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaryqccm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hvhpsytk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2yleejpwo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2adoplaul.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2xjibusmh.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2pitbhlzx.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gt2ddrfwyrw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkgzaweb.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbqzjths.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2fwqvyabg.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gt2zjbifcxm.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gt2eagooeng.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gt2zokodghj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gt2yywayijv.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gt2xglibfzx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckckbkts.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2mcyaiujc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gt2aeyyheir.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gt2jwnlegzs.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2jthwtmpd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmafqewl.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gt2crvwdinm.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gt2zoqzzhca.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gt2osmfwcec.html


<!-- 参考信息 -->